# 📊 Projeto Pipeline de Dados do Telegram 📊

## 🔍 Visão Geral
Este projeto tem como objetivo construir um pipeline de dados capaz de ingerir, processar, armazenar e expor mensagens de um grupo do Telegram. A partir desse histórico, é possível realizar análises e gerar insights relevantes.


## 🧱 Estrutura do Projeto
O pipeline está dividido em duas partes principais:

📥 Parte 1 — Captura via Bot API
- Utiliza os métodos GetMe e GetUpdates do Telegram Bot API para coletar mensagens diretamente do grupo.


🌐 Parte 2 — Captura via Webhook + AWS
- As mensagens são captadas por streaming via Webhook.
- Serviços da AWS são utilizados para automatizar essa coleta e diariamente em horários definidos. Também é realizado o armazenamento das mensagens e posteriormente consultas SQL.



## 🧰 Tecnologias Utilizadas
- Telegram: Criação do grupo e do bot para captura das mensagens.
- Amazon S3: Armazenamento dos dados em nuvem.
- AWS Athena: Execução de queries diretamente sobre os dados armazenados no S3.
- AWS Lambda: Criação das funções de processamento e transformação.
- AWS API Gateway: Redirecionamento dos dados recebidos para outros serviços da AWS.
- AWS EventBridge: Agendamento da execução diária da função ETL.
- SQL: Consultas e manipulação dos dados.
- Google Colab: Ambiente interativo para desenvolvimento e execução de notebooks.



✍️ Autor: Desenvolvido com dedicação por Taíta B. Ramos.

📚 Este projeto é parte da conclusão do módulo "Pipeline de Dados do Telegram" do curso de Analista de Dados da EBAC.

