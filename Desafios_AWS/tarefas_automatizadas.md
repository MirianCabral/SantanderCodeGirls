# Tarefas automatizadas com AWS Lambda e S3

## O AWS Lambda permite executar código sem precisar de servidores, sendo ideal para automatizar processos e integrar serviços da AWS, como S3 e DynamoDB.

### Integração com Amazon S3:

- O Lambda pode ser acionado automaticamente (via gatilho) quando um objeto é criado, alterado ou excluído em um bucket S3.

- Esse acionamento pode ser síncrono ou assíncrono.

- Também é possível enviar dados diretamente ao Lambda pela API, permitindo processar objetos específicos do S3.

### Integração com DynamoDB:

- O Lambda pode reagir a eventos no DynamoDB, como inserções ou atualizações de itens.

- Pode também gravar novos dados no DynamoDB a partir de outras fontes (ex: APIs externas).

- Essa integração é feita configurando o DynamoDB para enviar eventos ao Lambda, que executa o código desejado.
