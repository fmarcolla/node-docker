# node-docker
NodeJs application with docker.

# Criar Imagem
docker build -t marcolla/dockernode .

# Rodar Imagem
docker run -p 3000:3000 -d marcolla/dockernode