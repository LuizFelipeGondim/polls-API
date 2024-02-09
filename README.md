# voting-API


<b>Projeto desenvolvido durante a NLW Expert - Nodejs, no qual foi desenvolvido o back-end de uma aplicação de enquentes.</b>


## Instalação do app

> É necessário ter o Node.js e o Docker instalados na máquina.

```
npm install
docker compose up -d
```
<br>

- Crie o arquivo .env no diretório raiz e adicione a seguinte variável ambiente:

```
DATABASE_URL="postgresql://docker:docker@localhost:5432/polls?schema=public"
```
<br>

- Continue com os seguintes comandos e a aplicação estará pronta para uso:

```
npm prisma migrate dev
npm run dev
```
<br>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- TypeScript
- Nodejs
- Prisma
- Fastify
- Postgresql e Redis
- Web Socket
- Git e Github
