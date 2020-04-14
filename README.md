## Rastreador de sorrisos :)

##### [Live version](https://hemeur.herokuapp.com/) 

Essa ferramenta grava expressões faciais do usuário enquanto ele assiste a um vídeo e depois mostra as partes mais esngraçadas dele.

Ela assiste o usuário enquanto ele assiste o vídeo, e registra quando ele sorri.

<br>
Esse app utiliza:

 - Node.js
 - MongoDB
 - RabbitMQ
 - Docker
 
<br>

### Como funciona?

1. A câmera detecta as expressões
2. Node.js envia as expressões para o RabbitMQ
3. RabbbitMQ envia os dados para o MongoDB
4. As expresões e as posições no vídeo são anotadas e exibidas na tela


### Pré-requisitos

* Docker 
* Docker Compose

### Como iniciar

 ```
 docker-compose up --build
 ```
<br>

### Créditos
* [Rohan Sawant](https://github.com/CT83/Hemuer) pelo projeto.
