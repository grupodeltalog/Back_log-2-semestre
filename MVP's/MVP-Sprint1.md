# 📌 MVP - [API 1 Logística]

## 🎯 Objetivo do MVP
●	Qual problema resolve? A falta de uma ferramenta centralizada e acessível para a visualização dos dados do comércio exterior do Estado de São Paulo.

●	Qual hipótese será validada? Se os indicadores de comércio exterior forem apresentados em um dashboard interativo, então será possível analisar e identificar se o desempenho do estado está em ascensão, estagnação ou declínio.

●	Qual valor será entregue ao usuário final? Um dashboard interativo que permite analisar e comparar dados do comércio exterior, facilitando a compreensão dos indicadores logísticos e a tomada de decisão estratégica.

---

## 📝 Descrição da Solução
Desenvolvimento de um dashboard no Power BI focado na análise macro e microeconômica do comércio exterior do Estado de São Paulo. A solução integra bases públicas de dados para transformar volumes de exportação/importação em inteligência visual.
●	Principais funcionalidades: Visualização e comparação de dados de exportação e importação, análise por Unidades da Receita Federal (URFs), modais de transporte (marítimo, aéreo, rodoviário) e identificação dos principais países parceiros comerciais.

●	Gráficos interativos e cartões de visualização: Gráficos de barras, linhas e pizza para análise temporal e por categoria de produtos. Cartões dinâmicos que exibem o volume acumulado e a quantidade de produtos movimentados por URF selecionada.

●	Limitações conhecidas: Necessidade de inclusão de métricas detalhadas de valor por kg, valor FOB ($) e valor agregado dos produtos. Ajustes pendentes na padronização dos filtros do Power BI, especificamente na segmentação temporal contínua para o período de 2023 a 2025.

●	Escopo reduzido: Foco estrito nas visualizações essenciais de volumes de movimentação, principais URFs de entrada/saída e principais parceiros comerciais.


---

## 👥 Personas / Usuários-Alvo
●	Analista de Logística / Comércio Exterior: Necessita de dados consolidados para mapear rotas, gargalos de movimentação por URF e modais mais utilizados no estado.

●	Gestor / Tomador de Decisão Pública ou Privada: Busca acompanhar a balança comercial do estado para definir estratégias de investimento, expansão ou incentivos fiscais

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
| 01     | Modelagem da base de dados, criação dos cartões de KPI gerais (Importação/Exportação) e visualização preliminar por URF.                       | Em andamento  |
| 02     | Implementação dos gráficos por modal de transporte, parceiros comerciais e refinamento dos filtros interativos.                        | planejada|

---

## 📊 Critérios de Aceitação
●	O dashboard deve carregar todas as visualizações em menos de 5 segundos ao aplicar filtros.

●	Os dados exibidos nos cartões de KPI devem bater 100% com a soma dos registros filtrados na base de origem.

●	O filtro temporal deve permitir a seleção individual de anos (2023, 2024, 2025) ou do período acumulado.

●	Todas as URFs do Estado de São Paulo cadastradas na base devem constar no filtro de localização.


---

## 📈 Métricas de Avaliação
| Backlog de Produto| Backlog de Sprint	| Alocação de Tarefas	| Documentação no GitHub| 	Apresentação (Review)	| Conformidade Técnica| Total | 
|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-|
||||||
||||||||
---

## 🚀 Próximos Passos
1.	Corrigir a padronização dos filtros temporais referentes ao ciclo 2023–2025 no Power BI.
2.	Implementar as métricas de valor FOB ($) e valor em kg para enriquecer a análise de valor agregado.
3.	Validar a acurácia das somatórias com a base de dados oficial de comércio exterior (Comex Stat).
4.	Preparar o ambiente de homologação para o Review do MVP com os stakeholders.
---

## 📂 Anexos / Evidências
- 

- 

- 
