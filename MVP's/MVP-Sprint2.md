# 📌 MVP - [API 2 Logística]

## 🎯 Objetivo do MVP


---

## 📝 Descrição da Solução
A solução consiste em uma Pipeline de Inteligência de Dados (Business Intelligence) que realiza a extração, tratamento e modelagem dos dados brutos de acidentes da PRF. Os dados processados alimentam um dashboard interativo estruturado com as seguintes camadas:

-Camada de Visão Geral: Métricas consolidadas (KPIs) de ocorrências, vítimas, severidade e distribuição geográfica por Unidade Federativa (UF).

-Camada de Análise Setorial/Logística: Filtros dinâmicos voltados à frota pesada (caminhões, carretas, reboques) para isolar o impacto do transporte de cargas na segurança viária.

-Camada de Tendências: Gráficos comparativos entre o desempenho de estados específicos versus a média nacional, facilitando o diagnóstico preventivo e a alocação de recursos em infraestrutura e sinalização.


---

## 👥 Personas / Usuários-Alvo
-OBSERVATÓRIO Nacional de Segurança Viária(ONSV) 

-Objetivo: Identificar trechos de rodovias (BRs) com alta sinistralidade para direcionar obras de manutenção e reforço de sinalização e dimensionar a quantidade de acidentes graves e Mapear rotas rodoviárias de alto risco 


---

## 🔑 User Stories (Backlog do MVP)
| Rank | Prioridade | User Story                                                                                                                                              | Estimativa | Sprint |
|------|------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|------------|--------|
|  8   |    Alta	  | Como gestor público, desejo a implementação da base e dados SIM do Departamento DATASUS, para uma análise real da letalidade das rodovias federais.     |  8 Horas   |   2    |
|  9   |    Alta    | Como gestor público, desejo que a base de dados SIM esteja compatível com a base de dados da PRF, para evitar falsos positivos, perda de registros ou dados inutilizáveis.     | 8 Horas    |   2    |
|  10  |    Média   | Como gestor público, desejo ver o real desfecho de acidentes nas rodovias, podendo abranger os óbitos tardios para corrigir a distorção estatística e mapear os reais fatores de risco que transformam sinistros em fatalidades.     | 5 Horas   |   2    |
|  11  |   Média    | Como gestor público, desejo cruzar os dados de acidentes com o perfil socioeconômico das vítimas do DATASUS (Idade, Sexo e Escolaridade), para que eu possa identificar os públicos mais afetados e direcionar ações e projetos estratégicos de prevenção e intervenção de forma mais assertiva.     |   5 Horas  |   2    |
|  12  |    Alta    | Como gestor público, desejo observar a relação de óbitos com a Classificação Brasileira de Ocupações, para que eu possa identificar quais categorias de trabalhadores são as maiores vítimas de sinistros.     | 6 Horas   |   2    |



---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Extração e tratamento da base da PRF; Modelagem dimensional no Power BI; Criação dos cartões de KPI gerais de sinistros/gravidade e visualização inicial por UF/BR.                   | Em andamento  |
| 02     | Implementação de gráficos por tipo de veículo/modal de carga; Análise comparativa (Média Nacional x Estadual); Refinamento de filtros interativos, menu de navegação e testes de usabilidade. | planejada|

---

## 📊 Critérios de Aceitação
Acurácia e Confiabilidade dos Dados: 100% dos registros importados da PRF devem passar pela limpeza de dados (remoção de duplicatas, tratamento de campos nulos e padronização de tipos de veículos).
Desempenho da Ferramenta: As interações no Power BI (filtros de UF, ano e tipo de veículo) devem responder.
Filtro de Veículos Pesados: O dashboard deve permitir o isolamento claro das ocorrências envolvendo caminhões, carretas e tratores.
Navegação Intuitiva: Telas interligadas via menu de navegação, permitindo alternar facilmente entre a visão macro (Nacional) e micro (Trechos de BRs e Municípios).


---

## 📈 Métricas de Avaliação
| Backlog de Produto| Backlog de Sprint	| Alocação de Tarefas	| Documentação no GitHub| 	Apresentação (Review)	| Conformidade Técnica| Total | 
|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-|
||||||
||||||||
---

## 🚀 Próximos Passos

- Desenvolver um módulo de comparação entre indicadores de população, frota de veículos e acidentes.

- Criar rankings dinâmicos de estados e municípios com base no indicador selecionado.

- Implementar análise da evolução histórica dos indicadores por período.

## 📂 Anexos / Evidências
- Link do vídeo do entendimento do problema: 

- Dados tratados da DATASUS: 

- 5W2H:https://github.com/grupodeltalog/Back_log-2-semestre/blob/2f5ac12bf4a54cb8780a60045b60d49bfd915738/5W2H/5W2Hsp2.md

- Relatório: 
