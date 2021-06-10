# KAFKA-DOCKER

## Running docker-compose.yml

```bash
$ docker-compose up 
```
kafka will be available at kafka:9094 <br>
Control-panel will be available at http://localhost:9021

<br>

## Configurar /etc/hosts

A comunicação entre as aplicações se dá de forma direta através da rede da máquina.
Para isto é necessário configurar um endereços que todos os containers Docker consigam acessar.

Acrescente no seu /etc/hosts (para Windows o caminho é C:\Windows\system32\drivers\etc\hosts):
```
127.0.0.1 host.docker.internal
```
Em todos os sistemas operacionais é necessário abrir o programa para editar o *hosts* como Administrator da máquina ou root.

<br>

Se o container for parado, para inicia-lo novamente, é necessario rodar o comando "down" do docker-compose e o comando "up" para inicia-lo.
<br>
<br>

```bash
$ docker-compose down

$ docker-compose up -d
```
<br>
<center>Made with much ☕, by Lucas Duarte</center>
