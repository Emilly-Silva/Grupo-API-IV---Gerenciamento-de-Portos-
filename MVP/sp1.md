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
| Registro          |  Histórico |
|-------------------|-----------|
| MVP 1ª Sprint |  [1º Sp1 Print](../docs%20evidences/rg1.md) |



 



























