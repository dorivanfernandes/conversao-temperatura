Para executar o container é necessário executar os comandos na pasta raiz do projeto:

1. Build da imagem: docker image build -t dorivanfernandes/conversao-temperatura:v1 src/.
2. Criação do container: docker container run -d -p 9090:8080 dorivanfernandes/conversao-temperatura:v1
3. Pelo navegador, acesse localhost:9090

Imagem da aplicação executando:
![image](https://user-images.githubusercontent.com/36973335/160392218-80f9a3b1-54b0-45bd-aa69-bd76fd9c4e54.png)
