# SongApi - Serviços REST

Este projeto implementa os serviços da API REST para gerenciamento de músicas utilizando Spring Boot.

## Objetivo

Criar uma aplicação chamada SongApi com endpoints para listar, buscar, adicionar, atualizar e remover músicas.

## Configuração

- Ferramenta utilizada: Spring Tool Suite 4
- Porta padrão: 8080
- Contexto da aplicação: /api-song

## Endpoints disponíveis

- GET /api-song/allSongs: lista todas as músicas
- GET /api-song/findSong/{id}: busca uma música pelo id
- POST /api-song/addSong: adiciona uma nova música
- PUT /api-song/updateSong: atualiza uma música existente
- DELETE /api-song/removeSong: remove uma música

## Estrutura esperada

GitHub repository: bradesco-hbtn-microsservicos-java  
Directory: 0x02/servicos_API_REST

Arquivos:

- com/example/demo/SongApiApplication.java
- com/example/demo/SongController.java
- com/example/demo/SongRepository.java
- com/example/demo/Song.java

## Execução

Após iniciar a aplicação, acesse: http://localhost:8080/welcome

Você verá a mensagem:

**Bem-vindo ao serviço de músicas!**

