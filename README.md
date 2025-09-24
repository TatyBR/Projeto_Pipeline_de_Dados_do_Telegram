📊 **Projeto Pipeline de Dados do Telegram** 📊
🔍 Este projeto consiste em construir um *pipeline* de dados que irá ingerir, processar, armazenar e expor mensagens de um grupo do **Telegram** para que posteriormente seja possível realizar algumas análises tendo como base o histórico dessas mensagens.

O projeto está dividido em 2 partes:
- Parte 1: As mensagens do Telegram são captadas pelo próprio Bot API do Telegram usando os métodos GetMe e GetUpdates.
- Parte 2: As mensagens do Telegram são captadas via streaming com Webhook e são usados serviços da AWS para que isso ocorra diariamente em determinado momento.
  
🧰 Tecnologias Utilizadas:
Telegram: Criação do grupo e do bot.
Amazon S3: Armazenamento dos dados em nuvem.
AWS Athena: Execução de queries diretamente sobre os dados no S3.
AWS Lambda: Criação das funções necessárias.
AWS API Gateway: Definição da API para redirecionamento do dado recebido para outros serviços da AWS.
AWS Event Bridge: Ativa a função ETL diarimentes.
SQL: Para consultas e manipulação dos dados.
Google Colab: Ambiente interativo utilizado para a criação do notebook e execução de alguns códigos.

✍️ Autor: Projeto desenvolvido com dedicação por Taíta B. Ramos.
📊 Projeto desenvolvido para conclusão do módulo Projeto Pipeline de dados do Telegram do curso de Analista de Dados da EBAC.
