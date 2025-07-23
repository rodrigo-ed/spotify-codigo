# Spotify-Imersão Alura

Projeto desenvolvido durante a Imersão Alura, inspirado na interface do Spotify. O objetivo é praticar HTML, CSS e JavaScript, criando uma página interativa que simula funcionalidades básicas do Spotify, como busca de artistas e navegação por playlists.

## Estrutura do Projeto

- **index.html**: Página principal do projeto.
- **script.js**: Lógica de busca de artistas e manipulação da interface.
- **api-artists/artists.json**: Dados mockados dos artistas.
- **src/assets**: Imagens e ícones utilizados.
- **src/style**: Arquivos CSS para estilização.

## Funcionalidades

- Busca de artistas por nome.
- Exibição de cards de playlists.
- Layout responsivo e estilizado.
- Dados de artistas simulados via arquivo JSON.

## Como rodar o projeto

1. Clone este repositório.
2. Instale uma ferramenta para servir arquivos estáticos (ex: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VSCode).
3. Para busca de artistas, utilize um servidor local que sirva o arquivo `artists.json` como uma API REST (ex: [json-server](https://github.com/typicode/json-server)):
   ```sh
   npm install -g json-server
   json-server --watch api-artists/artists.json --port 3000
4. Abra o index.html em seu navegador.


## Tecnologias utilizadas

- HTML
- CSS
- JavaScript

## Créditos

- Ícones e imagens: Spotify e Icons8
- Inspirado na Imersão Alura

## Melhorias Futuras

- Adcionar a responsivida para mobile
