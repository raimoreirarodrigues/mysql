
### Pré-requisitos:
Necessário ter o docker instalado e configurado na máquina
    
### Instalação

Crie uma rede docker chamada desafio, caso não exista.

    //verifique se a rede desafio já existe.
    docker network ls

    //Caso a rede não exista, digite o comando abaixo para criá-la
    docker network create -d bridge desafio

    //Execute o comando para geração do container
    docker-compose build --no-cache

Por fim, suba o docker com o banco MySQL:
    docker-compose up -d




