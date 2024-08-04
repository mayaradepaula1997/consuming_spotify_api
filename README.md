
# Integração da API Spotify com Java e Spring Boot

## Descrição

Esta aplicação é um projeto desenvolvido para demonstrar como consumir a API do Spotify usando Java e Spring Boot. Utiliza Feign para simplificar a comunicação com a API externa, facilitando a integração e a manipulação dos dados.

## Funcionalidades

- Autenticação com Spotify: Permite que os usuários se conectem usando suas contas do Spotify, atraves da autenticação do token.
- Consumir a API: Os usuários podem ter acesso aos novos lançamentos de albuns.
- FeignClient de autenticação.
- Validar o comportamento do FeignClient

## Tecnologias Utilizadas

- *Java*: Linguagem de programação principal.
- *Spring Boot*: Framework para construção da aplicação.
- *Feign*: Biblioteca para simplificar a comunicação com a API do Spotify.
- *Spotify API*: API externa usada para buscar e gerenciar dados de músicas e playlists.

## Pré-requisitos

Antes de rodar a aplicação, você precisa ter:

- *JDK 17* ou superior
- *Maven* para gerenciamento de dependências
- *Credenciais da API do Spotify*: Crie uma aplicação no [Dashboard de Desenvolvedores do Spotify](https://developer.spotify.com/) e obtenha suas credenciais.
