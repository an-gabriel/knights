# knights challenge

Desafio para atuar em uma outsourcing

O desafio Knights visa a construção um sistema cadastro de heróis utilizando as 
seguintes tecnologias: 
• Vue.js 
• NodeJS (Express.js | NestJS) 
• MongoDB | Redi



## Dependências
- Node.js LTS
- Inversify
- Mongoose
- Docker

## Instalação para o com docker

Basta realizar o clone deste repositório.<br>

Em um diretorio de sua escolha execute o comando de clone do repositório:
```bash
git clone git@github.com:an-gabriel/knights.git
```

Após clonar o projeto, entre no diretório `knights` e execute o comando `docker-compose up`.<br>
Abaixo é possível visualizar o comando de execução do arquivo de setup:

```bash
cd ~/server && docker-compose up --build
```

Para realizar o login é necessario passar no body da requisição `username` e `password` conforme exemplo abaixo:

>___IMPORTANTE___: Para execução das rotas, está disponivel no projeto a pasta `./server/postman`, basta baixar a colection e a env para utilizar.

ps : Lembrei que preciso colocar o .env, geralmente utilizaria o secrets manager da aws para segurar variaveis de ambiente. 
