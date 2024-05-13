# Desafio Go Full Cycle
Neste desafio, você será convidado a criar uma imagem Docker em Go capaz de imprimir a mensagem "Full Cycle Rocks!!" ao ser executada.

## Requisitos
Docker instalado
Git instalado

## Passo a passo
1. Clone o repositório
2. Entre do diretório /go
3. Execute o seguinte comando para construir a imagem Docker:
```
docker build -t <seu-user>/golang:latest .
```
4. Execute a Imagem Docker:Após a construção da imagem, execute o seguinte comando para rodar o container:
````
docker run  <seu-user>/golang:latest
````
5. Alternativa: Download Direto da Imagem Docker Hub
````
docker pull frickdev/golang:prod
````

