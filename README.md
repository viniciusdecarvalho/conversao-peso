# conversao-peso

# Criar imagem Docker
docker image build -t conversao-peso:v1 .

# Criar container Docker
docker container run -d -p 80:80  --name conversao-peso conversao-peso:v1
