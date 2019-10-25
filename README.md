# dockerarticle
Ambiente de desenvolvimento PHP com Docker

# lista os containers dessa aplicação
docker-compose ps
# acessa o terminal do container php
docker container exec -it dockerarticle_php_1 bash
# para os containers
docker-compose stop
# para e remove os containers
docker-compose down
