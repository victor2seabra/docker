Se trata de uma ferramenta de containerização de aplicações

Com Docker podemos fazer deploy de containers que poderão ser executados em diversos lugares sem a necessidade de se adequar a especificações de cada máquina
# Arquitetura
# Imagens
São a planta baixa da definição de como o Container deve operar

Definimos uma imagem de acordo com as especificações que desejamos num arquivo denominado Dockerfile

Podemos criar um Container a partir de uma imagem ao executar `docker build .`

Podemos importar um imagem já existente num registry e executá-la, gerando o Container, usando `docker run`

A customização de imagens é comun pois, frequentemente gostaríamos de adicionar arquivos e/ou funcionalidades ao Container já em sua criação, como por exemplo instalação de um pacote Go

A estrutura de um Dockerfile é construída em camadas (layers) onde cada layer é uma instrução a ser realizada na criação do Container
# Containers
Se tratam dos executáveis que desejamos operar e que são definidos por uma Imagem
# Volumes
São formas persistentes de armazenamento de dados de Containers dentro do Docker
# Bind
São formas persistentes de armazenamento de dados de Containers no Host, isto é, na maquina em que está sendo executado o Container
# Namespaces
# overlayfs
# CLI
## docker build
## docker run
## docker start
## docker stop
## docker container prune
## docker container attach
## docker container stats
## docker container kill
## docker container logs
## docker container checkpoint
## docker container restore
## docker container commit
## docker container mount
## docker container unmount
## docker container update
## docker container exec
## docker container top
## docker container export
## docker container port
## docker image prune
## docker volume create
## docker volume mount
## docker volume prune
## docker volume delete
## docker volume exists
