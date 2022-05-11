# Instalação e Configuração

Instalar o aplicativo Xasmofarifado em:



## Requisitos
- RabbitMQ
- NodeJs



## Passo a passo

Iniciar Aplicações WEB:
```
npm install
npm start
```
Iniciar Aplicações do Back-end:
```
npm install
npm start
```

Iniciar RabbitMQ com Docker:
```
sudo docker run -it --rm --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3.9-management
```
