
### Pré-requisitos:
Necessário ter o docker instalado e configurado na máquina
    
### Instalação

    //verifique se a rede desafio já existe.
    docker network ls

    //Caso a rede não exista, digite o comando abaixo para criá-la
    docker network create -d bridge desafio

    //Entre no diretório mysql
    cd mysql

    //Execute o comando para geração do container
    docker-compose build --no-cache

    //suba o docker com o banco MySQL:
    docker-compose up -d

    //Verifique se o ambiente do banco está em execução:
    docker ps




