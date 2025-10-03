# 📌 MVP - ANÁLISE DE EFICIÊNCIA DE TERMINAIS PORTUÁRIOS

## 🎯 Objetivo do MVP
- Hoje os dados da ANTAQ estão distribuídos em múltiplas bases, com formatos complexos e não padronizados, o que dificulta análises rápidas de eficiência dos terminais portuários. Nossa hipótese validada é que foi possível extrair, limpar e correlacionar dados das bases da ANTAQ, gerando uma base inicial estruturada para cálculo de indicadores de eficiência portuária. O valor que será entregue ao cliente final, seria uma primeira versão da base de dados consolidada e confiável, servindo de insumo para análises de desempenho e eficiência portuária.

---

## 📝 Descrição da Solução
Nesta primeira entrega, foi desenvolvido um pipeline de tratamento de dados no Google Colab que:
- Extrai e organiza dados das bases AnoCarga e AnoAtracação (2021 a 2025).
- Seleciona apenas colunas de interesse para análises.
- Calcula o lead time de atracação (em horas).
- Realiza a correlação entre cargas e atracações (via IDAtracacao).
- Constrói um dataset final consolidado com códigos de país de destino, mercadoria e cidade de origem no Brasil.
  
Funcionalidades principais incluídas:
- Extração e pré-processamento de dados da ANTAQ.
- Cálculo do tempo médio de atracação.
- Junção de dicionários auxiliares (códigos de país, mercadoria e cidade).
- Geração de dataset inicial unificado.

Limitações conhecidas:
- Indicadores de eficiência ainda não foram implementados (ficam para a próxima etapa).
- Base consolidada contém apenas dados selecionados (escopo reduzido).

Escopo reduzido:
- Entrega mínima de uma base limpa e correlacionada, servindo como alicerce para indicadores e dashboards futuros.
  
---

## 👥 Personas / Usuários-Alvo
- **Persona 1:** breve descrição, necessidades e dores atendidas  
- **Persona 2:** breve descrição, necessidades e dores atendidas  

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| US1 | Como analista de dados, quero identificar e listar todas as fontes de dados disponíveis da ANTAQ, para que eu possa garantir que todas as informações necessárias para o projeto sejam consideradas.         | Alta       | 3   |
| US2 | Como desenvolvedor, quero criar e configurar o repositório no GitHub com README inicial, para que o time tenha um ambiente organizado para versionamento e colaboração.       | Média      | 1  |
| US3 | Como analista de dados, quero extrair os dados da ANTAQ utilizando Google Colab, para que eu possa automatizar o processo de obtenção dos dados para análise.     | Alta      | 2 |
| US4 | Como analista de dados, quero limpar e normalizar os dados extraídos, para que a base inicial esteja pronta e confiável para ser utilizada nas análises.    | Média     | 2 |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | [Funcionalidade X, Y]                        | Concluído|
| 02     | [Funcionalidade Z]                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário [ação principal]  
- O sistema deve registrar [evento importante]  
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








