
## Vamos lá!

Antes de tudo, é necessário que você tenha o git instalado, com isso, basta clonar o repositório.

`https://github.com/CaioCapua/gcb-test.git`

Antes de iniciar o projeto, é necessário a instalação das dependências, para isso rode o comando `yarn`

Após a instalação, roder um dos comandos abaixo para iniciar o projeto:

```bash
npm run dev
# or
yarn dev
```

## TypeORM

Rode o comando `yarn typeorm migration:run` para criar as tabelas de usuários e de especialidades

## Docker

Rode o comando `docker-compose up` para iniciar os containers

Após os a inicialização é possível testar as rotas através do insomnia ou pelo swagger, seguindo a seguinte link: [http://localhost:3333/api-docs/](http://localhost:3333/api-docs/)





