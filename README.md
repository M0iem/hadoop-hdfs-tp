# TP Hadoop HDFS avec Docker

## Description
Ce TP permet de maîtriser les bases de Hadoop HDFS à travers un cluster lancé avec Docker Compose.

## Architecture
- 1 NameNode (port 9870)
- 5 DataNodes
- 1 ResourceManager (port 8088)

## Lancer le cluster
docker compose up -d

## Se connecter au NameNode
docker compose exec namenode bash

## Arrêter le cluster
docker compose down
