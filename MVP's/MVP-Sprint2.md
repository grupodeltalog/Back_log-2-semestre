# 📌 MVP - [API 2 Logística]

## 🎯 Objetivo do MVP
O objetivo do MVP é implementar e compatibilizar as bases de dados SIM/DATASUS e PRF, aprimorando a qualidade e a consistência das informações utilizadas na análise dos óbitos. Busca-se validar a possibilidade de relacionar os registros das duas bases. Com isso, pretende-se entregar ao usuário final uma base de dados mais completa e confiável, capaz de ampliar a compreensão sobre as vítimas e os fatores associados à mortalidade.

---

## 📝 Descrição da Solução
A solução prevê a identificação de possíveis óbitos tardios relacionados aos registros de acidentes, permitindo uma análise mais precisa dos desfechos. Também contempla a verificação e utilização de informações sobre idade, sexo e escolaridade das vítimas, além da associação dos registros de óbitos à Classificação Brasileira de Ocupações (CBO). Essas informações serão disponibilizadas por meio de filtros de pesquisa e seleção no dashboard pelo Microsoft Power BI, permitindo explorar os dados de forma interativa, analisar o perfil das vítimas e identificar os grupos profissionais potencialmente mais afetados.

Dentre as limitações conhecidas, a base de dados do Sistema de Informações sobre Mortalidade (SIM), disponibilizada pelo DATASUS, apresenta diversas informações em formato de códigos, o que dificulta a identificação direta de seus significados. Para interpretar esses dados, é necessário utilizar o arquivo de conversão TABDO, disponibilizado pelo próprio DATASUS, e realizar o processamento no Google Colab, por meio de Python, para converter os códigos em descrições textuais compreensíveis e permitir sua utilização nas análises.

O escopo essencial desta etapa consiste na implementação da base de dados do SIM/DATASUS e na análise das informações disponibilizadas, validando sua utilização e integração com os dados da PRF. Essa entrega permitirá verificar a viabilidade de utilizar os dados de mortalidade nas análises.


---

## 👥 Personas / Usuários-Alvo
- Pessoa 1: Analista do ONSV (Observatório Nacional de Segurança Viária)

Profissional que utiliza dados de acidentes e mortalidade para analisar indicadores e identificar padrões relacionados aos óbitos no trânsito. Necessita de informações confiáveis e integradas para compreender melhor os fatores associados à mortalidade. A solução busca atender a essa necessidade por meio da consulta e análise interativa das informações no dashboard em Power BI.

 


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
| 01     |Extração e tratamento dos dados da PRF, visualizações nacionais e estaduais, filtros por tipo de veículo, ano e gravidade, indicadores por trechos rodoviários e gráficos comparativos no dashboard em Power BI.                   | Concluído  |
| 02     | Implementação da base SIM/DATASUS, compatibilização com os dados da PRF e preparação das informações para análise dos óbitos, perfil das vítimas e ocupações profissionais. | em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário consulte, compare os dados de mortalidade do SIM/DATASUS relacionados aos registros da PRF, por meio dos filtros de pesquisa e múltipla seleção, gráficos e com base nos indicadores apresentados apoiar na análise dos óbitos.
- Métricas coletadas: tempo de carregamento para visualizados do dados e facilidade no uso do filtros.


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

- 5W2H:https://github.com/grupodeltalog/Back_log-2-semestre/blob/67f3877a40e5421782d7fd4b774c8d27a51d0c6d/5W2H/5W2Hsp2.md

- Relatório: 
