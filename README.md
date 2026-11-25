# Avança Laís

Preparação para concursos educacionais da Avança SP.

## Banco v0.5.0 — 24/11/2026

Edital de referência: Limeira 01/2026, Diretor de Escola e Supervisor de Ensino (conforme retificações; segundo cargo a confirmar).

- [Banco canônico JSON](data/avanca_lais_banco_v0.5.json): 650 registros de 13 cadernos.
- [Índice analítico CSV](data/avanca_lais_indice_v0.5.csv).
- [Versão anterior v0.4](data/avanca_lais_banco_v0.4.json): histórico preservado.

| Lote | Fonte | Registros |
|---|---|---:|
| 001 | Garça — Diretor | 50 |
| 002 | Amparo — Diretor | 50 |
| 003 | Potim — Diretor, Supervisor, Coordenador | 150 |
| 004 | Varginha — Supervisor, Orientador | 100 |
| 005 | Caieiras — Diretor, Supervisor, Coordenador | 150 |
| 006 | Jeriquara — Orientador, Coordenador Pedagógico, Coordenador de Educação Infantil | 150 |

Classificação preliminar: A=360, B=88, R=117, P=12, X=6, D=67. A/B: 448 registros potencialmente aderentes (LP=87, MRL=83, INF=35, CE=243), sujeitos a auditoria e deduplicação cruzada.

## Critérios

A: aderência direta; B: aderência temática; R: revisão; P: pendente; X: excluída; D: duplicada. Preservar IDs e fontes, conferir gabaritos definitivos e vigência normativa. Excluir legislação municipal de outras cidades. Distinguir similaridade conceitual de duplicidade; não inferir duplicidade só pelo gabarito. Jeriquara: 17 duplicidades textuais e oito candidatas em revisão; os itens D herdam elegibilidade do canônico.

## Limitações

Índice referenciado aos PDFs, ainda sem enunciados e alternativas integrais. Não é simulador executável. Aderência preliminar; há páginas, imagens, normas e duplicidades pendentes. Capturas dos cadernos de Jeriquara não recuperadas; triagem pelo texto indexado, gabaritos dos coordenadores conferidos visualmente e do orientador pelo texto oficial. Questões com divergência de gabarito ou formulação em R. Caieiras: gabarito definitivo em espelho de terceiros, data de publicação não confirmada. Os 500 registros anteriores foram preservados integralmente. Integridade estrutural não implica validação independente de cada questão.

## Próximos lotes

Provas complementares de professores e de outros cargos superiores, priorizando concursos/blocos gerais ainda inéditos. Auditoria de classificação, legislação, gabaritos e duplicidades. Incorporar enunciados e alternativas antes do simulador. Manter versões cumulativas e histórico.

## Auditoria metodológica v0.5.1

- [Relações de repetição](data/auditoria_repeticoes_v0.5.1.json): 67 vínculos intraconcurso registrados, 18 candidatos intraconcurso e três comparações interconcursos (variantes/recorrências, não duplicatas). Nenhum vínculo literal interconcurso registrado; cobertura incompleta.
- [Protocolo de admissão e repetição](docs/protocolo_admissao_e_repeticoes.md): filtro por escolaridade, conteúdo programático, exigência observada e gabarito; piloto Itapecerica da Serra com programas gerais idênticos, importação pendente de inspeção dos itens.

Base v0.5 preservada sem alteração. Nenhuma nova questão incorporada nesta auditoria.

## Banco v0.6.0 — lote complementar 007-A

- [Banco JSON v0.6](data/avanca_lais_banco_v0.6.json) e [índice CSV v0.6](data/avanca_lais_indice_v0.6.csv).
- 675 registros, 14 cadernos de origem; A=378, B=90, R=122, P=12, X=6, D=67.
- 468 registros A/B (LP=96, MRL=90, INF=39, CE=243); deduplicação cruzada pendente.
- Vargem Grande Paulista 01/2026, Assistente Social (superior): programa geral coincidente, Q01–25 conferidas visualmente, gabarito definitivo de 28/09/2026. 18 A, 2 B, 5 R. Q26–50 não importadas nem triadas individualmente.
- Novo campo `exigencia_cognitiva`: reconhecimento/aplicação/análise, qualitativo, não medida de dificuldade. Ausente nos lotes anteriores, ainda não avaliados por essa rubrica.
- [Portal Vargem Grande Paulista](https://avancasp.selecao.net.br/informacoes/241/): gabaritos Q01–25 coincidentes entre Assistente Social/Controlador Interno/Enfermeiro Sanitarista e, separadamente, Arquiteto/Bibliotecário/Educador em Saúde Pública/Enfermeiro. São candidatos a blocos compartilhados; não duplicatas confirmadas. Bibliotecário e Controlador ainda não importados.
- [Portal Cachoeira Paulista](https://avancasp.selecao.net.br/informacoes/280/): programa superior compatível nas três disciplinas gerais (edital pp. 37–38), Professor I e Assistente Social são candidatos; PDFs dos cadernos excederam limite de recuperação. Gabarito definitivo 23/11/2026. Nenhum item importado.
- [Portal Itapecerica da Serra](https://avancasp.selecao.net.br/informacoes/266/): cadernos de Arquiteto e Enfermeiro excederam limite de recuperação. Gabarito definitivo disponível. Nenhum item importado nesta rodada.

650 registros anteriores preservados; índice e JSON verificados. Não há transcrição integral nem conclusão de deduplicação interconcurso. Priorizar segundo bloco superior de Vargem Grande Paulista e novos concursos compatíveis com PDFs recuperáveis.

## Banco v0.7.0 — lote complementar 007-B

- [Banco JSON v0.7](data/avanca_lais_banco_v0.7.json) e [índice CSV v0.7](data/avanca_lais_indice_v0.7.csv).
- 695 registros de 15 cadernos: A=397, B=90, R=123, P=12, X=6, D=67. A/B=487 (LP=106, MRL=99, INF=39, CE=243).
- Cachoeira Paulista, Processo Seletivo 04/2026, Psicólogo (superior), 08/11/2026: 20 itens gerais visualmente examinados; 19 A e 1 R (arredondamento monetário Q11). Gabarito definitivo de 23/11/2026, consultado em texto oficial.
- Q21–25 de Informática não recuperadas e não importadas; específicos não triados. Cadernos de Bibliotecário e Arquiteto de Vargem Grande Paulista, Farmacêutico de Itapecerica e Professor I de Cachoeira Paulista não puderam ser examinados nesta rodada.
- [Repetições 007-B](data/repeticoes_lote_007B.json): variante interconcurso sobre agente da passiva (VGP Q08 e CAP Q07), ambas preservadas; dois agrupamentos de respostas coincidentes em Cachoeira Paulista, ainda não confirmados por confronto dos textos.
- 675 registros anteriores preservados, identificadores e CSV conferidos. Sem transcrição integral nem auditoria cruzada exaustiva. Priorizar recuperação dos PDFs pendentes e preparação de corpus utilizável, sobretudo Informática.

## Lote visual 001 — material local

[Manifesto de integração](data/lote_visual_001_manifesto.json): 200 ocorrências de sete cadernos, incluindo 20 registros já existentes na v0.7; 25 duplicidades confirmadas de Itapecerica, 25 candidatos de Controlador Interno de Vargem Grande Paulista retidos para comparação com Assistente Social. 131 registros A/B no lote local, 43 R, 25 D, 1 X. Os recortes, textos-base numerados e visualizador de treino foram entregues localmente; não estão publicados no repositório público. Classificação, numeração e recortes preliminares; não somar o manifesto ao total da v0.7 antes de reconciliar IDs e auditoria.

## Banco v0.8.0 — integração do lote visual 001

- [Banco JSON](data/avanca_lais_banco_v0.8.json) e [índice CSV](data/avanca_lais_indice_v0.8.csv).
- 875 ocorrências de 21 cadernos, 695 anteriores preservadas + 180 novas (20 IDs coincidentes no manifesto não duplicados). A=506, B=93, R=165, P=12, X=7, D=92. A/B=599, ainda preliminares e sujeitos à auditoria.
- Distribuição A/B: LP=146, MRL=132, INF=61, CE=260.
- 25 novas duplicatas intraconcurso Arquiteto/Farmacêutico e 25 candidatas de Controlador Interno/Assistente Social. Gabaritos e classificações herdados do lote local, não revalidados item a item nesta integração.
- Os assets continuam locais e vinculados por manifesto; não publicados. O banco JSON não é por si só simulador executável. Próxima etapa: obter PDFs originais dos cadernos de gestão para revisão visual, gabaritos e recortes.

## Banco v0.9.0 — auditoria do lote visual 002

[JSON](data/avanca_lais_banco_v0.9.json) · [CSV](data/avanca_lais_indice_v0.9.csv). 875 ocorrências preservadas; A=513, B=93, R=163, P=4, X=7, D=95. 350 respostas confrontadas com quatro gabaritos oficiais definitivos: nenhuma divergência. Potim: 35 pares Supervisor/Coordenador confirmados por texto, imagem e gabarito (25 gerais e 10 específicos). Amparo: oito classificações recuperadas, sete A e uma R. 300 novos recortes locais de seis cadernos, não publicados no repositório. Caderno Garça ainda não recebido. Pacote local cumulativo: 500 ocorrências, 346 A/B em treino preliminar; revisão visual individual e testes de navegador ainda pendentes. Nenhuma repetição literal interconcurso detectada na comparação dos textos extraídos dos cinco cadernos com camada textual; não é auditoria exaustiva de suportes, variantes ou demais provas.

## Banco v0.10.0 — lote visual 003

[JSON](data/avanca_lais_banco_v0.10.json) · [CSV](data/avanca_lais_indice_v0.10.csv). 875 ocorrências (515 A, 94 B, 149 R, 110 D, 7 X). 350 gabaritos cotejados localmente neste lote (300 novos, 50 de Garça já cotejados no lote 002), sem divergências. 25 pares em Caieiras e 25 em Jeriquara, dos quais 15 duplicatas novas em relação ao banco anterior. Quatro pendências de classificação resolvidas (duas A, uma B, uma R). 850 ocorrências e 589 A/B no pacote visual local cumulativo; faltam 25 ocorrências do caderno de Assistente Social de Vargem Grande Paulista. Recortes e conteúdo integral não publicados no GitHub; revisão visual individual e testes completos no navegador pendentes. Caieiras edital 01/2024 e Jeriquara processo seletivo 01/2025 registrados separadamente dos IDs históricos. Comparação interconcurso inicial de 465 itens com texto e sem marcação D: 46 pares candidatos com similaridade textual cosseno >=0,60 (TF-IDF de n-gramas de caracteres 4–5, retirados cabeçalhos de questão); os primeiros resultados mostram que fórmulas recorrentes de enunciado e alternativas podem inflar similaridade, não representam duplicatas comprovadas.

## Banco v0.11.0 — fechamento da coleta principal

[JSON](data/avanca_lais_banco_v0.11.json) · [CSV](data/avanca_lais_indice_v0.11.csv). 875 ocorrências de 21 cadernos, todas com recortes disponíveis no pacote local cumulativo dos lotes 001–004. 515 A, 94 B, 124 R, 135 D, 7 X; 609 A/B preliminares. Distribuição: LP=147, MRL=132, INF=66, CE=264. Assistente Social e Controlador Interno de Vargem Grande Paulista: 25 pares intraconcurso confirmados por comparação visual e máscaras de pixels nas páginas 2–7, com gabaritos anteriormente cadastrados coincidentes. Preservadas ambas as ocorrências, 25 R convertidas em D. Nenhum novo ID. ZIP local e referências de imagens verificados, sintaxe JS aprovada; navegador bloqueou testes por política do ambiente. Imagens não publicadas no GitHub. Aderência por cargo, revisão individual, auditoria interconcursos e testes de interação permanecem pendentes. Próxima etapa: engenharia reversa por seleção independente, eixo, autor, norma e modelo de cobrança, com análise de lacunas frente ao edital retificado.

## Engenharia reversa — primeira leitura da v0.11

- [Relatório analítico estruturado](analysis/engenharia_reversa_v0.11.json): posições originais, eixos, autores explícitos, incidência por seleção, IDs de evidência e limites metodológicos. 740 registros históricos não-D; 609 A/B preliminares; 16 blocos gerais em nove seleções.
- [Requisitos do aplicativo e próximos tratamentos](docs/requisitos_app_e_engenharia_reversa.md): interface simples sem status internos ou filtros de concurso, simulado padrão, treino por áreas/assuntos, desempenho, copiar questão para Sofia, dicas fundamentadas.

Nenhum registro da base v0.11 alterado. Frequências preliminares; auditoria de taxonomia, aderência por cargo, formatos, gabaritos problemáticos e duplicidade interconcurso ainda necessária.

## Banco v0.12 — primeira auditoria de conteúdo

[JSON](data/avanca_lais_banco_v0.12.json) · [CSV](data/avanca_lais_indice_v0.12.csv) · [Matriz retificada de Limeira](analysis/matriz_limeira_v0.1.json). 36 itens visualmente examinados; 24 R→A, 3 R→X, 4 A→X, 5 R→R. 875 IDs preservados e gabaritos inalterados. 535 A, 94 B, 97 R, 135 D e 14 X; 629 A/B preliminares (LP=158, MRL=141, INF=66, CE=264). Tags secundárias manuais nos 36 itens, não em todo o banco. Retificação I remove Decreto 11.556/2023 para ambos; artigos 2, 3 e 5 do ECA fora dos intervalos expressos; quatro questões da Lei Lucas recuperadas após cotejo normativo. Matriz de lacunas por etiquetas, não auditoria exaustiva. Pacote visual v0.11 e interface permanecem inalterados nesta rodada; não publicar como treino final sem sincronização. Próximos: 97 R, revisão dos A/B e detalhamento das lacunas locais e novas normas.

## Banco v0.13 — segunda auditoria normativa

[JSON](data/avanca_lais_banco_v0.13.json) · [CSV](data/avanca_lais_indice_v0.13.csv) · [Matriz de Limeira v0.2](analysis/matriz_limeira_v0.2.json). 23 registros R examinados: 17 A, 1 B, 3 X, 2 R. 875 IDs e gabaritos preservados. 552 A, 95 B, 76 R, 135 D, 17 X; 647 A/B preliminares (LP=158, MRL=141, INF=66, CE=282). Uma questão real sobre Lei 14.533/2023 recuperada, reduzindo a lacuna indexada. Decreto 7.611/2011 excluído por revogação; duas questões de inclusão com atribuição normativa imprecisa mantidas em revisão. Variante LDB art. 8 Garça Q47/Amparo Q40 preservada. Sem questões autorais; fichas com resumo e links oficiais para lacunas confirmadas são proposta futura. O visualizador local ainda não foi sincronizado com v0.12/v0.13. Auditoria de A/B, escopo por cargo, recortes e interações continua pendente.

## Avança Laís — entrega v1.0 / banco v0.14

[Banco canônico](data/avanca_lais_banco_v0.14.json). 649 itens no catálogo de entrega (158 LP, 143 MRL, 66 INF, 282 CE); 74 R, 135 D e 17 X retidos. Mantidos os 875 IDs e gabaritos. Pacote local `Avanca_Lais.zip`: `index.html`, `data.json` e 922 imagens WebP, com verificação de integridade. SHA-256 do ZIP verificado: `487e5f560d7182fa8e2d6f73a7217ff09fc6a2f290c5a5d97347fa658521f779`. Interface e imagens ainda não enviadas ao GitHub: a transferência de arquivos binários do ambiente local requer Git ou outro cliente autorizado. Para publicação, extrair o pacote, copiar `index.html`, `data.json` e `img/` para a raiz de `main`, e habilitar GitHub Pages em Settings → Pages → Deploy from a branch → main / (root). Não usar o HTML autônomo superior a 100 MB. A URL esperada é https://sociosofia.github.io/avanca-lais/ (não validada como publicada). O repositório é público: verificar permissões de reprodução das provas antes de disponibilizar os recortes publicamente.
