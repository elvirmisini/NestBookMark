# Bookmark project with NodeJs(NestJs) and PostgreSQL

![Build Status](https://img.shields.io/badge/nestjs-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Build Status](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Build Status](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Build Status](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
The project is fully tested and functional with CRUD operations, all you need to do is:

- Clone the repo
- Install the packages with:

```sh
npm install
```

- Create .env file with:

```sh
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE?schema=public"
JWT_SECRET="SECRET"
```

- Create migrations with:

```sh
npx prisma migrate dev
```

- Start project with:

```sh
npm run start:dev
```
