# Model Chat

Modelo de chat assíncrono usando Python, Django, Websocket, Javascript, Bootstrap, Docker, dentre outras tecnologias. Nele é possível a troca de mensagens entre usuários em chats privados ou grupos.

![chat](model_chat/static/img/duo_chat.gif)

## Docker

Para rodar os containers, basta ter o [Docker](https://www.docker.com/) e o [Docker-compose](https://docs.docker.com/compose/) instalados. Após isso basta digitar o seguinte comando no diretório raíz:

```shell
$ sudo docker-compose up --build
```

## Ngrok

Caso queira visualizar o projeto ou compartilhar de forma online, basta ter o [Ngrok](https://ngrok.com/) instalado e configurado no seu computador, e garantindo que os containers estão em pleno funcionamento digitar o seguinte comando no diretório raíz:

```shell
$ ngrok http http://localhost:8000
```