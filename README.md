# Pure-JPA - Digital Innovation One

O objetivo deste projeto é aprender os principais conceitos do JPA.
## Getting Started

1. Clone este projeto
2. Execute na raiz deste projeto o seguinte comando:
```
mvn clean package
```
3. Iniciando...


### Pré-requisitos

Para executar este projeto, você deve instalar o MySQL ou Docker. Para facilitar a instalação do MySQL
Eu criei o docker-compose.yaml para instalar o MySQL.


Se você não sabe como instalar o docker e o docker-compose, assista ao tutorial no seguinte link:
- Windows: https://www.youtube.com/watch?v=_9AWYlt86B8
- Linux: https://www.youtube.com/watch?v=bpbcu36t7g0&t=6s
- Mac: https://www.youtube.com/watch?v=mbSsh40_8WM

Para instalar o MySQL usando o Docker, execute o seguinte comando no caminho raiz deste projeto:

```
docker-compose up
```

Se você tiver dificuldade em entender este readme.md, assista ao vídeo a seguir para entender o docker-compose.

https://www.youtube.com/watch?v=Qw9zlE3t8Ko.

### Para entrar no MYLSQ...Por linha de comando.

No terminal, digite o seguinte comando:
```
docker container ls
```
Copie o id da imagem do MYSQL, e digite:
```
docker exec -it ID_IMAGEM_DOCKER bash
```

Feito isso, digite
```
mysql -u root -p
```
E aperte ENTER...pronto! Entrou no MYSQL.