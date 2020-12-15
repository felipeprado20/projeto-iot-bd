# Projeto - Internet of Things 
Camada de armazenamento do projeto da disciplina SSC0952 - Internet das Coisas utilizando um banco de dados com MongoDB e Docker.

# Descrição do Projeto
O projeto consiste em modelar um banco de dados para armazenar os dados da aplicação IoT, os quais foram tratados na camada de micro-serviço.

## Instalaçao e configuração

### Instalando o Docker
 $ sudo apt-get update
 $ sudo apt-get install docker-ce docker-ce-cli containerd.io
 
### Instanciando o mongo no Docker
docker run --name MongoDB -p 9001:27017 -d mongo

Onde o comando -p define a porta interna (9001) e a porta externa (27017)

