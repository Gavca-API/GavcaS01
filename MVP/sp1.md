# 📌 MVP - GAVCA API

## 🎯 Objetivo do MVP 
- Projetar e implementar um dashboard interativo focado no monitoramento de cargas especiais e perigosas. A solução consolida indicadores sobre os principais players do mercado e mapeia fluxos logísticos (origem/destino), permitindo o acompanhamento da evolução temporal das operações. 
-  Realizar o tratamento e a padronização dos registros governamentais originários do IBAMA. O objetivo é converter dados brutos em uma estrutura de análise funcional. 
- Prover uma base de análise funcional, fundamentada em dados reais e selecionados criteriosamente. O objetivo é garantir que a visualização seja objetiva e livre de ruídos, permitindo uma interpretação clara e direta dos indicadores apresentados

---

## 📝 Descrição da Solução
- Um painel interativo que conecta as origens aos destinos, permitindo visualizar a densidade do transporte de cargas especiais no território nacional.  
- Implementação de camadas de verificação que asseguram a consistência dos dados antes da fase de análise. 
- Tratamento de Dados: Conversão da base bruta do IBAMA em informações funcionais.
- Filtros Essenciais: Seleção por tipo de carga e players para validar a eficiência da ferramenta.  

---

## 👥 Personas / Usuários-Alvo
- Marcus Nascimento – Coordenador do curso e cliente do projeto
- IPEM – Instituição parceira/órgão relacionado ao projeto
- Prof. Jean Costa – Professor orientador
---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| 1    | 1      | Como analista de dados, quero identificar as regiões com maior procura do uso das cargas perigosas, para compreender onde há maior demanda e apoiar decisões logísticas mais eficientes                   | 5         | 1      |                                                                                     
| 2   | 1      | Como analista de dados, quero identificar quais são as regiões que apontam uma evolução de compras das cargas perigosas, para analisar tendências de crescimento e apoiar a tomada de decisão                                   | 5          | 1      |
| 3   | 1     | Como analista de dados, quero tratar e organizar os dados utilizando o Google Colab, para garantir que as informações estejam limpas, padronizadas e prontas para análise                                                                                                                                                        | 7        | 1      |
| 4  | 1      | Como analista de dados, quero construir um dashboard no Power BI, para visualizar os dados de forma clara e apoiar a tomada de decisão.                                                                                                                                                        | 5          | 1      |
| 5   | 1      | Como analista de dados, quero montar uma apresentação em PowerPoint, para comunicar os resultados do projeto de forma clara e objetiva ao cliente                                                                                                                                                       | 2         | 1      |
| 6  | 2     | Como analista de dados, quero identificar os maiores centros de emissão e os principais centros de entrega desses materiais, para compreender o fluxo logístico e otimizar a distribuição                   | 5          | 2     |                                                                                     
| 7  | 2       | Como analista de dados, desejo identificar quais são os tipos de modais mais solicitados para a entrega de cargas perigosas dos clientes, a fim de analisar a eficiência dos transportes e apoiar melhorias logísticas                                   | 5          | 2      |
| 8   | 2      | Como analista de dados, quero tratar e organizar os dados utilizando o Google Colab, para garantir que as informações estejam limpas, padronizadas e prontas para análise                                                                                                                                                        | 7          | 2     |
| 9  | 2      | Como analista de dados, quero construir um dashboard no Power BI, para visualizar os dados de forma clara e apoiar a tomada de decisão.                                                                                                                                                        | 5          | 2     |
| 10  | 2     | Como analista de dados, quero montar uma apresentação em PowerPoint, para comunicar os resultados do projeto de forma clara e objetiva ao cliente                                                                                                                                                       | 2          | 2     |
| 11  | 3    | Como analista de dados, quero identificar quais são as empresas que mais vendem e armazenam cargas perigosas, para mapear os principais participantes do mercado e analisar sua atuação no setor                   | 5          | 3    |                                                                                     
| 12  | 3      | Como analista de dados, quero identificar quais são os planos de ações de sustentabilidade adotados por empresas e órgãos governamentais para os cuidados com o meio ambiente, a fim de avaliar práticas ambientais e propor melhorias.                                  | 5          | 3     |
| 13   | 3      | Como analista de dados, quero tratar e organizar os dados utilizando o Google Colab, para garantir que as informações estejam limpas, padronizadas e prontas para análise                                                                                                                                                        | 7          | 3     |
| 14  | 3    | Como analista de dados, quero construir um dashboard no Power BI, para visualizar os dados de forma clara e apoiar a tomada de decisão.                                                                                                                                                        | 5          | 3     |
| 15 |  3    | Como analista de dados, quero montar uma apresentação em PowerPoint, para comunicar os resultados do projeto de forma clara e objetiva ao cliente                                                                                                                                                       | 2          | 3    |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 1   | Alta       | Como analista de dados, quero identificar as regiões com maior procura do uso das cargas perigosas, para compreender onde há maior demanda e apoiar decisões logísticas mais eficientes                   | 5         | 1   |                                                                                     
| 1   | Alta       | Como analista de dados, quero identificar quais são as regiões que apontam uma evolução de compras das cargas perigosas, para analisar tendências de crescimento e apoiar a tomada de decisão                                   | 5          | 1      |
| 1  | Alta       | Como analista de dados, quero tratar e organizar os dados utilizando o Google Colab, para garantir que as informações estejam limpas, padronizadas e prontas para análise                                                                                                                                                        | 7        | 1      |
| 1  | Alta       | Como analista de dados, quero construir um dashboard no Power BI, para visualizar os dados de forma clara e apoiar a tomada de decisão.                                                                                                                                                        | 5          | 1      |
| 1   | Baixa       | Como analista de dados, quero montar uma apresentação em PowerPoint, para comunicar os resultados do projeto de forma clara e objetiva ao cliente                                                                                                                                                       | 2         | 1      |

---

## 📊 Critérios de Aceitação
- MVP deve permitir que o usuário acompanhe indicadores de forma clara e dinâmica
- Painel com indicadores amplos sobre o status das cargas perigosas para suporte à gestão e controle operacional.  
- Métricas coletadas: [exemplo: tempo de resposta, taxa de uso]  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
