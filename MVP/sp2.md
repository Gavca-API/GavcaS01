# 📌 MVP - [GAVCA API]

## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:  
- Este MVP tem como propósito refinar o diagnóstico logístico sobre a movimentação de produtos perigosos, mapeando os modais utilizados, tipos de transporte, principais malhas rodoviárias e os municípios estratégicos nesse fluxo. O dashboard centraliza esses dados em um layout visual intuitivo, dinâmico e de rápida compreensão, transformando dados brutos em inteligência logística de fácil interpretação.
  
- A expansão dos indicadores logísticos no painel permitirá um entendimento mais aprofundado dos rotas utilizadas, dos padrões de movimentação e da geolocalização das cargas perigosas no território nacional.
  
- O projeto agrega novas métricas de desempenho e filtros avançados que mapeiam a relevância de modais, veículos, eixos rodoviários e municípios na movimentação de materiais perigosos. Essa estrutura garante uma camada de inteligência de dados aprofundada, capacitando o usuário a rastrear gargalos logísticos, áreas críticas e tendências operacionais de forma totalmente centralizada e intuitiva.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.  
- Disponibilizar um painel interativo construído em Power BI, alimentado por dados públicos do IBAMA referentes ao fluxo de produtos perigosos e rejeitos sólidos. A plataforma engloba diagnósticos sobre as mercadorias mais transportadas, matrizes de transporte, matriz de Origem e Destino (OD), polos urbanos com maior fluxo, segmentação regional e KPIs logísticos estratégicos. Para sustentar a solução, as fontes brutas são submetidas a etapas de higienização, padronização, modelagem e consolidação utilizando Python, resultando em um repositório analítico estruturado e otimizado para o cruzamento de informações no dashboard.
  
- Na versão atual, o sistema depende da qualidade e do preenchimento das bases públicas do IBAMA, o que pode afetar a precisão de algumas análises específicas. Algumas filtragens avançadas e cruzamentos mais complexos também estão sendo desenvolvidos, o que limita um pouco o nível de detalhe nesta primeira entrega do MVP.
  
- O escopo atual do MVP é entregar uma solução que funcione de verdade para analisar a logística de cargas perigosas. Agora, na segunda sprint, estamos focados em rodar a base de dados unificada, mapear os principais padrões de transporte e montar um painel interativo que mostre os indicadores de forma simples e visual.
---

## 👥 Personas / Usuários-Alvo
- Marcus Nascimento – Coordenador do curso e cliente do projeto
- IPEM – Instituição parceira/órgão relacionado ao projeto
- Prof. Jean Costa – Professor orientador  

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| 6  | Alta       | Como analista de dados, quero identificar os maiores centros de emissão e os principais centros de entrega desses materiais, para compreender o fluxo logístico e otimizar a distribuição                   | 5          | 2     |                                                                                     
| 7  | Alta       | Como analista de dados, desejo identificar quais são os tipos de modais mais solicitados para a entrega de cargas perigosas dos clientes, a fim de analisar a eficiência dos transportes e apoiar melhorias logísticas                                   | 5          | 2      |
| 8   | Alta       | Como analista de dados, quero tratar e organizar os dados utilizando o Google Colab, para garantir que as informações estejam limpas, padronizadas e prontas para análise                                                                                                                                                        | 7          | 2     |
| 9  | Alta       | Como analista de dados, quero construir um dashboard no Power BI, para visualizar os dados de forma clara e apoiar a tomada de decisão.                                                                                                                                                        | 5          | 2     |
| 10  | Baixa       | Como analista de dados, quero montar uma apresentação em PowerPoint, para comunicar os resultados do projeto de forma clara e objetiva ao cliente                                                                                                                                                       | 2          | 2     |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais | Status |
|--------|--------------------|--------|
| 02 | Módulo de análise e comparação de eficiência entre diferentes modais de transporte em rotas e fluxos coincidentes | Concluído |
| 02 | Mapeamento, classificação e análise estatística da matriz de modais de transporte utilizados nos fluxos logísticos | Concluído |
| 02 | Análise das principais rodovias utilizadas | Concluído |
| 02 | Identificação das cidades responsáveis pelo transporte de cargas | Concluído |
| 02 | Expansão dos filtros e refinamento das análises | Concluído |


---

## 📊 Critérios de Aceitação
- O MVP deve permitir que a gente visualize com clareza os modais mais utilizados e os tipos de veículos que realizam o transporte das cargas.
- O sistema deve trazer análises focadas nos eixos rodoviários e nos municípios envolvidos no fluxo do transporte.
- O usuário deve conseguir combinar e cruzar informações logísticas com facilidade, usando filtros práticos para encontrar o que precisa.
- O painel deve garantir uma navegação limpa e organizada, além de ser totalmente responsivo para o usuário.  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP: 3 usuários 
- Feedback qualitativo : em andamenro 
- Agilidade para identificar padrões e comportamentos logísticos.
- Automatização da análise de rotas e modais, reduzindo o esforço manual do usuário.

---

## 🚀 Próximos Passos
- Análises regionais mais detalhadas.
- Novas métricas de segurança no transporte.
- Implementação de filtros mais robustos.
- Melhorias no layout do dashboard.
- Integração de novas fontes de dados.  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
