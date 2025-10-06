
---

# ☁️ Arquitetura AWS para Auto Processamento

## 🧩 Descrição do Projeto

Este projeto tem como objetivo **modelar e documentar uma arquitetura em nuvem AWS voltada para auto processamento de dados.
A modelagem foi realizada utilizando a ferramenta [diagrams.net (Draw.io)](https://app.diagrams.net/), com o foco em representar visualmente os principais serviços AWS e fluxos de dados automatizados envolvidos em uma solução escalável e segura.

---

## 🎯 Objetivos

Criar uma arquitetura escalável e resiliente na AWS. 
Demonstrar o fluxo automatizado de ingestão, processamento e armazenamento de dados**.
Utilizar boas práticas de arquitetura em nuvem**, como alta disponibilidade, segurança e custo otimizado.
Desenvolver habilidades práticas em **modelagem de arquiteturas AWS** no Draw.io.

---

## 🏗️ Componentes da Arquitetura

A arquitetura proposta inclui (ajuste conforme seu projeto):

Amazon S3 – Armazenamento dos dados brutos e processados.
AWS Lambda – Funções serverless para processamento automático.
Amazon SNS / SQS – Comunicação e orquestração entre serviços.
AWS Glue / Step Functions – Gerenciamento de pipelines de dados.
Amazon CloudWatch – Monitoramento e logs do processo.
IAM– Controle de acesso e segurança.

---

## 🔄 Fluxo de Processamento

1. Os dados são carregados automaticamente no S3 Bucket (Raw Data).
2. Um evento S3 aciona uma função Lambda para processar ou transformar os dados.
3. Os resultados são armazenados em outro bucket S3 (Processed Data).
4. Logs e métricas são enviados ao CloudWatch.
5. Notificações de sucesso ou erro são enviadas via SNS.

---

## 🛠️ Ferramentas Utilizadas

AWS (Amazon Web Services) – modelagem de serviços de nuvem
[Draw.io](https://app.diagrams.net/) – criação do diagrama da arquitetura
GitHub – versionamento e documentação do projeto



---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos de:

Arquitetura em nuvem AWS.
Integração entre serviços serverless.
Automação de pipelines de processamento.
Representação visual de sistemas complexos no Draw.io.

---

## 👩‍💻 Autora

Bruna Stefany
Projeto desenvolvido para o curso de AWS Cloud Fundamentals
“Transformando ideias em arquiteturas escaláveis na nuvem.”

---

