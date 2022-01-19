Para executar o container é necessário executar os comandos na pasta raiz do projeto:

1. Build da imagem: docker image build -t dorivanfernandes/conversao-temperatura:v1 src/.
2. Criação do container: docker container run -d -p 9090:8080 dorivanfernandes/conversao-temperatura:v1