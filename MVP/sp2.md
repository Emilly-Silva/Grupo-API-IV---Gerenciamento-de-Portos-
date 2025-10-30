# 📌 MVP - ANÁLISE DE EFICIÊNCIA DE TERMINAIS PORTUÁRIOS - 2ª Sprint

## 🎯 Objetivo do MVP
- Com base na estrutura de dados desenvolvida na 1ª Sprint, esta segunda entrega teve como foco consolidar e disponibilizar o dataset final, implementar filtros e rankings de terminais, integrar o backend em Python à base de dados, e criar o protótipo inicial da plataforma de BI no Power BI.
O objetivo validado foi comprovar que é possível analisar e comparar a eficiência entre terminais portuários brasileiros utilizando dados públicos da ANTAQ, tratados e estruturados em um fluxo automatizado.
O valor entregue ao cliente é uma plataforma analítica funcional, que permite o acompanhamento de métricas de eficiência portuária de forma visual, interativa e confiável.

---

## 📝 Descrição da Solução
Nesta primeira entrega, foi desenvolvido um pipeline de tratamento de dados no Google Colab que:
- Extrai e organiza dados das bases AnoCarga e AnoAtracação (2021 a 2025).
- Seleciona apenas colunas de interesse para análises.
- Calcula o lead time de atracação (em horas).
- Realiza a correlação entre cargas e atracações (via IDAtracacao).
- Constrói um dataset final consolidado com códigos de país de destino, mercadoria e cidade de origem no Brasil.
  
**Funcionalidades principais incluídas:**
- Extração e pré-processamento de dados da ANTAQ.
- Cálculo do tempo médio de atracação.
- Junção de dicionários auxiliares (códigos de país, mercadoria e cidade).
- Geração de dataset inicial unificado.

**Limitações conhecidas:**
- Indicadores de eficiência ainda não foram implementados (ficam para a próxima etapa).
- Base consolidada contém apenas dados selecionados (escopo reduzido).

**Escopo reduzido:**
- Entrega mínima de uma base limpa e correlacionada, servindo como alicerce para indicadores e dashboards futuros.
  
---

## 👥 Personas / Usuários-Alvo
- **Analista de Dados Portuários:**
Suas necessidades consistem em ter acesso a dados organizados e confiáveis para análises. Eliminando a necessidade de limpar e padronizar manualmente bases brutas da ANTAQ.

- **Gestor Portuário / Tomador de Decisão:**
Suas necessidades consistem em acompanhar métricas de eficiência operacional. Passando a ter uma base inicial estruturada para gerar relatórios de desempenho.   

---

## 🔑 User Stories (Backlog do MVP)
| ID  | Prioridade   | User Story | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| ID1   |    Alta   | Como analista, quero preparar e disponibilizar o dataset final em formato definido (CSV), para que ele esteja pronto para ser utilizado no desenvolvimento do projeto.     | 2        |      
| ID2   | Média     | Como analista, quero filtrar os dados relevantes para as análises, para que o projeto trabalhe somente com informações úteis e otimize o processamento.     | 4       |     
| ID3   |  Alta     | Como desenvolvedor de BI, quero construir um protótipo inicial do dashboard no Power BI, para que possamos validar o formato e funcionalidades básicas da visualização     | 5     | 
| ID4   |    Alta   | Como usuário do dashboard, quero visualizar um ranking dos terminais baseado em eficiência, para que eu possa facilmente identificar os melhores e piores desempenhos.     |  4    | 
| ID5   | Média     | Como usuário do dashboard, quero utilizar filtros básicos para segmentar os dados, para que eu possa analisar informações específicas conforme a necessidade.     |  2     |
| ID6   | Média   | Como desenvolvedor backend, quero integrar o código Python que manipula os dados com o dataset em CSV, para que o sistema funcione de forma integrada e automatizada.     | 3      |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Extração de dados, limpeza, normalização, merge e dataset inicial consolidado.                        | Concluído|
| 02     |  Implementação de indicadores de eficiência, ranking e protótipo em Power BI.                        | A fazer |
| 03     |  Análises de tempos de operação e paradas, módulo de cargas movimentadas, testes de usabilidade, documentação final, apresentação e publicação do projeto no GitHub.                        | Planejado |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir a geração de uma base inicial consolidada (Carga + Atracação).
- O sistema deve registrar corretamente o lead time de atracação em horas.
- Métricas coletadas: completude dos dados (sem valores ausentes nas colunas-chave) e consistência de datas/IDs.

---

## 📈 Métricas de Validação
- Feedback qualitativo sobre clareza e usabilidade da base.
- Confirmação de que a base atende às primeiras necessidades de análise (indicadores na próxima sprint).

---

## 🚀 Próximos Passos
- Ajustes pós 1ª Sprint.
- Implementar indicadores de eficiência (tempo médio de operação, produtividade por terminal, etc.).
- Disponibilizar dataset final em formato CSV no GitHub.
- Criar protótipo inicial em Power BI para visualização dos resultados. 

---

## 📂 Anexos / Evidências
| Registro          |  Histórico | Relatório MVP|
|-------------------|-----------|-----------|
| MVP 2ª Sprint |  [Print](../docs%20evidences/rg2.md) | A Fazer |
