

# Desafio Code Girl AWS: Upload de Arquivos com Processamento e Registro no DynamoDB



Case: Sistema de Armazenamento de Notas Fiscais



Cliente fazendo um Armazenamento de arquivo:



   Cliente ---Arquivo---> S3---trigger--->Lambda Function---Arquivo---> DynamoDB <---API Gateway





  Cliente fazendo uma consulta:



   Cliente ---query---> API Gateway ---chama lambda--->DynamoDB



Lambda(Python) checa se o arquivo está correto 



Ferramentas utilizadas: 



- LocalStack

