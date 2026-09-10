# patrimonio_aula05

## Projeto Back-end — Os Códigos

O projeto Os Códigos consiste no desenvolvimento de uma aplicação back-end para gerenciamento e controle de patrimônios. A aplicação foi desenvolvida utilizando Node.js e o framework Express, com os dados armazenados inicialmente em um arquivo dados.json.

O sistema permite realizar operações básicas de gerenciamento de patrimônios, possibilitando cadastrar, listar, atualizar e excluir registros. Cada patrimônio possui informações como identificador, item, local onde está registrado, data de registro, valor e número de patrimônio.

A aplicação disponibiliza diferentes rotas HTTP para manipulação dos dados:

## GET / — Lista todos os patrimônios cadastrados.
## POST / — Permite cadastrar um novo patrimônio.
## DELETE /:id — Exclui um patrimônio utilizando seu ID.
## PATCH /?id= — Atualiza os dados de um patrimônio específico.

O servidor é executado na porta 3000, utilizando o Express para receber e processar as requisições HTTP. O projeto também utiliza o middleware express.urlencoded() para realizar o tratamento dos dados enviados nas requisições.

Como armazenamento, o sistema utiliza um arquivo JSON contendo exemplos de patrimônios, como notebooks, celulares e outros itens. Dessa forma, o projeto demonstra na prática conceitos fundamentais de desenvolvimento back-end, como servidores HTTP, APIs REST, métodos HTTP, rotas, requisições, respostas, parâmetros e manipulação de dados.

O objetivo principal do projeto é desenvolver uma API simples e funcional para controle de patrimônio, servindo também como prática dos fundamentos de desenvolvimento de aplicações back-end com Node.js e Express.

## Tecnologias utilizadas: 
* Node.js
* JavaScript
* JSON
* HTML
## Evidencias
![foto1](./foto1)
![foto2](./foto2)
