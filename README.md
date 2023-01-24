# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### Imagem docker

Para rodar a imagem docker

```
cd ./src
docker container run -d --rm -p 8080:8080 damatomos/conversao-temperatura
```

### Kubernetes

Para rodar o kubernetes

```
cd ./k8s
kubectl apply -f deployment.yaml
```
