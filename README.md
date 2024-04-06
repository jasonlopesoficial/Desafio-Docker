# Desafio Full Cycle - Nginx com Node.js

Este desafio apresenta a solução referente ao módulo de DOCKER.

O desafio consiste em renderizar uma mensagem na tela utilizando as tecnologias nginx e node.js.

Ao executar a aplicação, deverá ser salvo um registro no bando de dados (MySQL), em seguida, a página deverá apresentar 
a mensagem ```Full Cycle Rocks!```, logo abaixo uma lista com os registros do banco.

Nota: A página deverá ser construída em node mas será acessada pelo nginx através de um proxy reverso!

---

### Para rodar a aplicação utilize o docker-compose.

```
docker-compose up -d 
```

Dentro de alguns instantes a aplicação estará no ar.

---

### Para acessar, digite o seguinte endereço no navegador:

[http://localhost:8080/](http://localhost:8080/)

---
OBS: se for apresentado o erro 502, por favor atualize a página.
