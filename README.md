Projeto Policia

# Baixar Linux Debian/ubuntu
- Docker pull debian/ubuntu

# Criar Conteiner
- docker run -it --name "Nome do container"
- docker run -it --name Policia

Primeiros Comandos
# mostrar comandos existentes
- Docker 

# Mostrar insformações do container
- docker inspect

# Mostrar conteiner que esta rodando
- Docker ps

# Mostrar imagens existentes
- docker images

# Baixar imagem do sistema operacional linux
- docker pull "nome da OS"
- docker pull ubuntu

# Criar container
- docker run -it --name "nome"

# Parar container
- docker stop "ID"

#Iniciar container
- docker start "ID"

# Atualizar container
- apt-get update

# Entrar no container
- docker attach "ID"

# Criar imagen a partir do container
- docker commit -a "nome da imagem" -m "nome do contatiner" "ID" ubuntu/imagem:1.0
- docker commit -a Policia -m ubuntu e74f5cde22c9 ubuntu/imagem:1.0

# Remover container
- docker rm -f

# Remover imagens
- docker rmi -f

# Passo a Passo
Instale o docker
Levante a rede virtual
Reinicie o windows
Abra o docker/tertminal
- Baixe a imagem do sistema operacional "docker pull ubuntu"
- Crie o container "docker run -it --name Policia ubuntu"
- 
