## Tarefas Automatizadas com Amazon S3 e AWS Lambda

Este projeto foi desenvolvido durante o laboratório da DIO com foco em automação serverless utilizando serviços da AWS.

O objetivo foi entender na prática como automatizar processamento de arquivos utilizando integração entre Amazon S3, AWS Lambda e Amazon DynamoDB.

## Tecnologias Utilizadas:
Amazon S3
AWS Lambda
Amazon DynamoDB
AWS CloudFormation
LocalStack
  
 ##  O que foi realizado
Criação de bucket S3
Upload automatizado de arquivos
Configuração de eventos no S3
Processamento automático com Lambda
Registro de informações no DynamoDB
Simulação de ambiente AWS utilizando LocalStack

🧩 Fluxo da Arquitetura
Amazon S3
   ↓
Evento de Upload
   ↓
AWS Lambda
   ↓
Processamento do Arquivo
   ↓
Amazon DynamoDB

 ## Aprendizados

Durante o laboratório, aprendi melhor como funciona uma arquitetura serverless orientada a eventos.

Também consegui entender:

integração entre serviços AWS;
automação de tarefas;
processamento assíncrono;
uso do LocalStack para desenvolvimento local;
monitoramento e troubleshooting de funções Lambda.
 

##  Insights importantes
Serverless reduz necessidade de gerenciamento de infraestrutura.
Eventos automatizados facilitam arquiteturas escaláveis.
LocalStack ajuda muito em ambientes de desenvolvimento e testes.
Lambda é extremamente útil para processamento assíncrono.

## Referências
Documentação oficial da AWS
Conteúdo prático da DIO
