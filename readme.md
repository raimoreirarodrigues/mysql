
### Pré-requisitos:
Necessário ter o docker instalado e configurado na máquina
    
### Instalação

    //Clone o projeto
    git clone https://github.com/raimoreirarodrigues/mysql.git
    
    //verifique se a rede desafio já existe.
    sudo docker network ls

    //Caso a rede não exista, digite o comando abaixo para criá-la
    sudo docker network create -d bridge desafio

    //Entre no diretório mysql
    cd mysql

    //Execute o comando para geração do container
    sudo docker-compose build --no-cache

    //suba o docker com o banco MySQL:
    docker-compose up -d

    //Verifique se o ambiente do banco está em execução:
    docker ps




