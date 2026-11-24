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
