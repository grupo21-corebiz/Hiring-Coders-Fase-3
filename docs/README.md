<h1 align="center">Hiring Coders FASE#3 - Desafio Final</h1>
<p align="center">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white"/>
  <img src="https://img.shields.io/badge/VTEX IO-%23FFFFFF.svg?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTA0IiBoZWlnaHQ9IjQzMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCiA8dGl0bGU+VlRFWF9pY29uX3BpbmtfUkdCPC90aXRsZT4KIDxnPgogIDx0aXRsZT5iYWNrZ3JvdW5kPC90aXRsZT4KICA8cmVjdCBmaWxsPSJub25lIiBpZD0iY2FudmFzX2JhY2tncm91bmQiIGhlaWdodD0iNDMzIiB3aWR0aD0iNTA2IiB5PSItMSIgeD0iLTEiLz4KIDwvZz4KIDxnPgogIDx0aXRsZT5MYXllciAxPC90aXRsZT4KICA8cGF0aCBmaWxsPSIjZjcxOTYzIiBpZD0ic3ZnXzIiIGQ9Im00NjUuMTQ2MzMyLDEuNDgyNjg4bC0zNzQsMGMtMjksMCAtNDcuNTcsMzAuODMgLTM0LDU2LjQ2bDM3LjQzLDcwLjg0bC02Ny44NCwwYTI0Ljk0LDI0Ljk0IDAgMCAwIC0yMi4wNiwzNi41NmwxMjAuMzMsMjI3Ljc1YTI0Ljk0LDI0Ljk0IDAgMCAwIDQ0LjA4LDBsMzIuNjgsLTYxLjUybDQxLDc3LjYyYzE0LjQzLDI3LjMgNTMuNTIsMjcuMzUgNjgsMC4wOGwxODcuNDYsLTM1Mi43NmMxMy4yNSwtMjQuOTUgLTQuODMsLTU1LjAzIC0zMy4wOCwtNTUuMDN6bS0xNjgsMTUwLjcybC04MC44MywxNTIuMTRhMTYuNiwxNi42IDAgMCAxIC0yOS4zMywwbC04MC4wNSwtMTUxLjVhMTYuNiwxNi42IDAgMCAxIDE0LjY3LC0yNC4zNWwxNjEuMjgsMGExNi4xNSwxNi4xNSAwIDAgMSAxNC4yNiwyMy43MXoiIGNsYXNzPSJhIi8+CiA8L2c+Cjwvc3ZnPg==&logoColor=white"/>
</p>

## Tópicos
:small_blue_diamond: [Descrição do projeto](#descrição-do-projeto)<br>
:small_blue_diamond: [Principais Objetivos do projeto](#principais-objetivos)<br>
:small_blue_diamond: [Pré-requisitos](#pré-requisitos)<br>
:small_blue_diamond: [Como executar a aplicação](#executando-a-aplicação)<br>
:small_blue_diamond: [Workaround](#workaround)<br>
:small_blue_diamond: [Paleta de cores](#paleta-de-cores)<br>
:small_blue_diamond: [Agradecimentos](#agradecimentos)<br>

## Descrição do projeto
O projeto desenvolvido pela equipe 21 - patrocinador **Corebiz** - é uma API que engloba outras duas APIs: **API VTEX** para servir os projetos e os pedidos vendidos e **API AWS Gateway** para gerenciamento de venda ativa na AWS. O front-end foi projetado com a temática, cores, missão e valores do patrocinador **Corebiz**

## Principais Objetivos
:heavy_check_mark: Construção do FRONT-END do site [Corebiz](https://www.corebiz.ag/pt/) utilizando o framework **Vtex IO**.<br>
:heavy_check_mark: Criação de servidor de cadastro de leads utilizando **dynamodb, lambda** e **API Gateway** da **AWS** .<br>
:heavy_check_mark: Criação da API VTEX para servir os pedidos vendidos.<br>
:heavy_check_mark: Criar um item no adm do VTEX para trazer o conteúdo das leads cadastradas na API Gateway AWS<br>

## Pré-requisitos
- Node.js
- Yarn
- VTEX IO

## Executando a aplicação
A aplicação está disponivel para usúarios da plataforma Hiring Coders/VtexIO.
- Instale o Node.js. Se você estiver usando um MAC, instale também Yarn;
- Execute `npm i -g vtex` em seu terminal se estiver usando Windows ou `yarn global add vtex` se estiver usando MAC;
- Execute `vtex login hiringcoders202121` em seu terminal.
- Depois de fazer login, execute `vtex whoami` para confirmar a conta e a área de trabalho em que você se encontra.
- Finalmente, use `vtex link` dentro do projeto.

## Workaround
Para linkar a aplicação o seguinte workaround deve ser utilizado:
- Remover o `"admin": "0.x"` do `manifest.json`
```json
  "builders": {
	...
    "admin": "0.x"
  },
```

- Usar `vtex link` no terminal
- Ainda com o terminal aberto com o hotload da vtex, adicionar o  `"admin": "0.x"` dentro do `manifest.json`

Isso fará com que o modulo pule a verificação da vtex.


### Paleta de cores:

- background: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- big_text: #ffffff ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)

- title1: #f1c233 ![#f1c233](https://via.placeholder.com/15/f1c233/000000?text=+)

- title2: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- subtitle: #666666 ![#666666](https://via.placeholder.com/15/666666/000000?text=+)

- Button: #2680EB ![#2680EB](https://via.placeholder.com/15/2680EB/000000?text=+)

- ButtonOnMouseOver: #2870C6 ![#2870C6](https://via.placeholder.com/15/2870C6/000000?text=+)

- Button_font: #ffffff ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+)

- Framework1: #F1C233 ![#F1C233](https://via.placeholder.com/15/F1C233/000000?text=+)

- Framework2: #2680EB ![#2680EB](https://via.placeholder.com/15/2680EB/000000?text=+)

- Framework3: #953764 ![#953764](https://via.placeholder.com/15/953764/000000?text=+)

- Framework4: #CE7C3E ![#CE7C3E](https://via.placeholder.com/15/CE7C3E/000000?text=+)

- grayScale1: #434343 ![#434343](https://via.placeholder.com/15/434343/000000?text=+)

- grayScale2: #666666 ![#666666](https://via.placeholder.com/15/666666/000000?text=+)

- grayScale3:#999999 ![#999999](https://via.placeholder.com/15/999999/000000?text=+)

- grayScale4: #B7B7B7 ![#B7B7B7](https://via.placeholder.com/15/B7B7B7/000000?text=+)

- MediaSlide1background: #FF6E60 ![#FF6E60](https://via.placeholder.com/15/FF6E60/000000?text=+)

- MediaSlide2background: #91A7D0 ![#91A7D0](https://via.placeholder.com/15/91A7D0/000000?text=+)

- ContactAreaBackgroung: #F5F5F5 ![#F5F5F5](https://via.placeholder.com/15/F5F5F5/000000?text=+)

- ContactAreaPlaceHolderfontcolor: #D0D0D0 ![#D0D0D0](https://via.placeholder.com/15/D0D0D0/000000?text=+)

- formFontColor: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

- ContactAreaButton: #D0D0D0 ![#D0D0D0](https://via.placeholder.com/15/D0D0D0/000000?text=+)

- ContactAreaButtonActive: #000000 ![#000000](https://via.placeholder.com/15/000000/000000?text=+)

## Agradecimentos
Agradeço ao pessoal do Slack por ter ajudado logo quando estava precisando, e ao pessoal do Hiring Codes e Vtex IO pela oportunidade de usar a plataforma.
