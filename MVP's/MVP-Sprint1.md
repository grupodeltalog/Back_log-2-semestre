# 📌 MVP - [API 1 Logística]

## 🎯 Objetivo do MVP
Desenvolver uma solução analítica interativa em Power BI fundamentada em dados abertos da Polícia Rodoviária Federal (PRF). O objetivo principal é subsidiar a tomada de decisão no setor público e logístico, permitindo a identificação de trechos críticos (blackspots) em rodovias federais (BRs), a análise comportamental de veículos pesados de carga e a avaliação do impacto da gravidade dos sinistros na infraestrutura e fluidez logística do país.

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
| 1    |     Alta   | Como gestor público, desejo uma base de dados extraídos da PRF, para possuir uma fonte oficial e confiável de informações.                              |4 Horas     | 1      |
| 2    |     Alta   | Como gestor público, desejo dados tratados e organizados, para torná-los utilizáveis e garantir precisão nas análises.                                                                   |6 Horas     | 1      |
| 3    |     Alta   | Como gestor público, desejo uma visualização Nacional e estadual por meio de filtros para uma análise mais refinada.                                             |3 Horas     | 1      |
| 4    |     Alta   | Como gestor público, desejo aplicar filtros por tipo de veículo, ano do evento e gravidade do sinistro, para que eu possa isolar o comportamento de veículos pesados e identificar cenários de alto risco.    |3 Horas     | 1      |
| 5    |     Média   | Como gestor público, desejo visualizar indicadores que demonstrem a ocorrência de sinistros em determinados trechos das BRS, para identificar pontos de foco e possíveis falhas de infraestrutura e sinalização.  | 6 Horas     | 1      |
| 6    |     Alta   | Como gestor público, desejo visualizar gráficos comparativos entre os estados e a média nacional para análise comparativa.                                                                                                                                         | 4 Horas     | 1      |
| 7    |     Alta   | Como gestor público, desejo todas as funções citadas anteriormente integradas a um Dashboard na ferramenta Power BI para trazer uma visualização clara e interativa, dando inicio ao sistema de análise logística.  | 7 Horas     | 1      |


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


## 📂 Anexos / Evidências
- 

- 

- 
