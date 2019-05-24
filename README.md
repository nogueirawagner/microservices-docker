# microservices-docker
Orquestrando micro serviços com docker compose

Este exemplo é para demonstrar o uso do docker compose, gerenciando e orquestrando os serviços.
Para exemplificar tem uma aplicação em jquery com as operações de CRUD irá rodar em um container utilizando a imagem do nginx, o backend rodará em um container utilizando a imagem do node e o banco de dados NoSQL irá rodar em uma imagem do mongo.

Veja como ficou o arquivo docker-compose.yml para a execução do exemplo.
Para executar basta executar o comando docker-compose up.
