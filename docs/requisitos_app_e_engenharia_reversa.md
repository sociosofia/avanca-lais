# Avança Laís — requisitos do aplicativo e análise preliminar
Data: 24/11/2026. Decisões de produto registradas a partir da conversa; não representam funcionalidades já implementadas.

## Experiência da candidata
- Manter identidade visual do piloto aprovado. Interface em português, responsiva e sem filtros de município, ano, edital ou caderno.
- Início: simulado completo, estudo por assunto, meu desempenho e dicas para a prova.
- Simulado completo: escolher apenas cargo-alvo (Diretor de Escola / Supervisor de Ensino, segundo cargo a confirmar). Gerar automaticamente 50 itens (10 LP, 10 MRL, 5 INF, 25 CE), 180 minutos, ordem de disciplinas conforme matriz adotada. Se houver alteração do edital, parametrizar por cargo. Não forçar seleção de subáreas.
- Estudo dirigido: uma ou mais áreas e, opcionalmente, um ou mais assuntos; filtros simples. Se nenhum assunto for selecionado, usar toda a área. Quantidade de questões ajustável, sem pedir escolhas desnecessárias.
- Apenas questões elegíveis e conferidas no catálogo de treino. Status A/B/R/D/X, justificativas técnicas e filtros de proveniência não aparecem durante a resolução. Questões R, X e duplicadas não entram no sorteio; manter ocorrência no banco de pesquisa. Não substituir lacunas de oferta por questões inadequadas; informar apenas disponibilidade insuficiente de itens quando necessário.
- Preservar ordem original das alternativas, texto-base, linhas fixas, destaques, gráficos, imagens e equações. No simulado, manter contexto compartilhado e evitar repetição do mesmo ID canônico.
- Modo simulado: mostrar resultado após finalizar, com revisão dos erros. Modo estudo: botão Ver resposta para correção quando solicitado; registrar resposta dada antes de revelar gabarito. Manter marcação pessoal para revisão opcional (distinta do status interno de auditoria).
- Copiar questão para estudar com a Sofia: incluir enunciado integral, alternativas na ordem original, texto-base relevante, resposta da candidata, gabarito oficial, assunto e referência. Quando houver figura, oferecer recorte original para anexar; não fingir que texto copiado contém imagem. Enquanto transcrição não estiver revisada, usar alternativa de exportação do recorte e metadados, nunca texto incompleto apresentado como integral.
- Desempenho: acertos/tentativas e percentual por área e assunto; quantidades de questões únicas respondidas, histórico de simulados, erros recorrentes. Distinguir primeira tentativa de repetição e questões reveladas sem resposta. Dados locais por padrão. Não confundir frequência no banco com probabilidade de acerto.
- Dicas para sua prova: padrões históricos, autores recorrentes, assuntos com botão de treino. Exibir evidência e linguagem não determinista (ex.: 14 de 16 blocos), sem prometer que cairá. Cruzar com edital retificado por cargo antes de publicar dicas. Incluir conteúdos previstos mas pouco ou nada representados no acervo como lacunas, não como irrelevantes.

## Engenharia reversa — primeira leitura do banco v0.11
Relatório detalhado: ../analysis/engenharia_reversa_v0.11.json.
875 ocorrências; 135 D; 740 registros não-D (inclusive R/X para fins históricos); 609 A/B preliminares. 16 blocos gerais de nove seleções (município como proxy); específicos educacionais de sete seleções. Independência e deduplicação interconcurso ainda não comprovadas.

| Padrão | Evidência |
|---|---|
| Q01 interpretação/tipologia | 14/16 blocos, nove seleções |
| Q02 semântica | 8/16 blocos, sete seleções |
| Semântica Q01–03 | 12/16 blocos, nove seleções |
| Redação oficial Q08–10 | 15/17 itens de redação oficial |
| Windows Q21 ou Q22 | 14/16 blocos, nove seleções |
| Q23 Word | 7/16 |
| Q24 Excel | 7/16 |
| Q47 LDB | 4/13 registros não-D nessa posição; sinal fraco |

Autores explicitamente atribuídos no índice histórico: Freire 7 itens/5 seleções; Luckesi 8/5 (7 A/B em 4 seleções); Arroyo 6/5 (5 A/B em 5 seleções). Não misturar atribuição temática e citação explícita. Saviani, Lück e Libâneo constam de duas seleções cada por atribuição explícita; não inferir importância no edital somente pela frequência. A autoria e o escopo da bibliografia precisam de auditoria fina.

Não há evidência de posição fixa de crase, preposição ou advérbio. Matemática tem posição temática menos estável. 122 dos 609 itens A/B têm formato ausente ou pendente, e a codificação é de eixo único. A análise de modelos de cobrança exige revisão das transcrições e tags secundárias. Legislação contabilizada via prefixo LEG_; normas implícitas em CE podem não estar identificadas.

## Próxima etapa de tratamento
1. Auditar taxonomia (macroárea, subárea, tags secundárias, autor explícito/obra, norma/artigo, operação cognitiva e formato) e 124 R (69 CE, 28 MRL, 14 INF, 13 LP).
2. Cruzar cada tema com o edital retificado de cada cargo; mapear lacunas, inclusive normas locais e novas, em trilha própria.
3. Investigar os candidatos de similaridade interconcurso e preservar variantes. Produzir dicas com denominadores de seleções e blocos, priorizando aderência ao edital.
4. Validar recortes/texto-base, transcrição integral para copiar, gabaritos e fluxo em navegador antes da publicação. Só então liberar corpus de treino final.
