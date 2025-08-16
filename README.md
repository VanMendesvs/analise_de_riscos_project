# 🛡️ Análise de Risco de Crédito: Automação e Classificação de Clientes

### **📄 Ficha Técnica do Projeto**

Este `README.md` detalha o projeto de análise de dados focado na identificação do perfil de clientes com risco de inadimplência, com o objetivo de automatizar o processo de análise de crédito para o Banco “Super Caja”.

### **Objetivo Geral**

Transformar dados de clientes brutos em insights acionáveis para classificar os solicitantes de crédito em diferentes categorias de risco, melhorando a eficiência e a precisão na avaliação de pedidos de empréstimo.

### **Problema de Negócio / Hipóteses Centrais**

O projeto buscou responder a perguntas-chave e validar hipóteses sobre o perfil de clientes com risco de inadimplência, incluindo:

* Qual a taxa de inadimplência geral do banco?
* É possível classificar os clientes em diferentes categorias de risco (Baixo, Médio, Alto)?
* A idade e o salário de um cliente têm relação com a sua probabilidade de inadimplência?
* O histórico de atrasos de pagamento é um fator de risco significativo?

### **Tecnologias e Ferramentas Utilizadas**

* **Google BigQuery:** Utilizado para armazenamento, manipulação e tratamento dos dados (ETL - Extração, Transformação e Carga).
* **Looker Studio:** Ferramenta principal para a construção de um dashboard interativo para análise e visualização de dados.
* **SQL:** Linguagem utilizada para consultas e manipulação de dados no BigQuery.
* **Google Slides:** Para a criação da apresentação executiva dos resultados.
* **Loom:** Para a gravação da apresentação final.

### **Fontes de Dados**

O projeto utilizou um conjunto de dados do banco que inclui informações demográficas e financeiras dos clientes, como idade, salário, número de dependentes, taxa de endividamento e histórico de atrasos de pagamento.

### **Estrutura do Projeto**

O projeto foi desenvolvido nas seguintes etapas principais:

* **Coleta e Importação de Dados:** As tabelas de dados foram conectadas e importadas para o Google BigQuery.
* **Tratamento de Dados (BigQuery):**
    * Identificação e tratamento de valores nulos.
    * Limpeza e padronização de dados.
    * Criação de novas colunas e categorização de dados (ex: `faixa_etaria`, `faixa_salarial`).
* **Modelagem e Análise de Hipóteses (Looker Studio):**
    * **KPIs Gerais:** Scorecards com o total de clientes, taxa de inadimplência geral e a distribuição de risco (Alto, Médio, Baixo).
    * **Hipóteses Validadas:**
        * **Idade x Inadimplência:** Clientes mais jovens (até 35 anos) apresentam uma taxa de inadimplência mais alta.
        * **Salário x Inadimplência:** A inadimplência é mais concentrada nas faixas salariais mais baixas.
        * **Histórico de Atrasos:** O número de atrasos de pagamento é um dos indicadores mais fortes de risco de inadimplência.
* **Geração de Conclusões e Recomendações:**
    * Com base nos insights validados, foram elaboradas conclusões e recomendações estratégicas para a automação do processo de crédito e a mitigação de riscos.
* **Apresentação dos Resultados:**
    * Criação de slides executivos no Google Slides.
    * Gravação de vídeo individual apresentando os resultados, conclusões e recomendações do projeto.

### **Resultados e Ganhos para o Negócio**

* ✅ **Eficiência Operacional:** O projeto permite a aprovação automática de clientes de Baixo Risco, que representam **66,3% da base de dados**, liberando a equipe para focar em casos mais complexos.
* 🛡️ **Mitigação de Riscos:** O modelo identifica claramente os casos de Alto Risco, contribuindo para a solidez financeira do banco ao reduzir a exposição a empréstimos não reembolsáveis.

### **Links do Projeto**

| Recurso | Link |
| :--- | :--- |
| 📹 **Apresentação em Vídeo** | [https://www.loom.com/share/06c344b8e1a142d296fed187a0986f86?sid=ca33b251-d4b4-4a21-b14a-96cea3641538](https://www.loom.com/share/06c344b8e1a142d296fed187a0986f86?sid=ca33b251-d4b4-4a21-b14a-96cea3641538) |
| 📊 **Dashboard Interativo** | [https://lookerstudio.google.com/reporting/4d715f02-8ea3-4582-9999-0e48b9dc9ce6](https://lookerstudio.google.com/reporting/4d715f02-8ea3-4582-9999-0e48b9dc9ce6) |
| 📄 **Documentação Completa** | [https://coda.io/d/Documentacao-Projeto-3_dn1aqyGh68d/Documentacao-Projeto-3_suGQnGQr#_luW-6JVp](https://coda.io/d/Documentacao-Projeto-3_dn1aqyGh68d/Documentacao-Projeto-3_suGQnGQr#_luW-6JVp) |
| ☁️ **Base de Dados** | [BigQuery – Console do Google Cloud](https://console.cloud.google.com/bigquery) |

**Feito por:**

Vanessa Mendes da Silva
