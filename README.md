# *Spring Boot - Api Reativa*

Projeto de API reativa com Spring Boot 

Stack utilizada

<ul>
  <li>Java8</li>
 <li>spring webflux</li>
 <li>Spring data</li>
 <li>dynamodb</li>
 <li>junit</li>
 <li>sl4j</li>
 <li>reactor</li>
</ul>

### Executar dynamo:

na pasta em que o jar está baixado: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

para listar as tabelas criadas: aws dynamodb list-tables --endpoint-url http://localhost:8000

documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
