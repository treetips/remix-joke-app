# Remix Joke App

- [Jokes App Tutorial](https://remix.run/docs/en/v1/tutorials/jokes#jokes-app-tutorial)

## Features

- VSCode
- Node.js
- Remix
- Prisma

## setup

```sh
# create tables
$ npx prisma db push
Environment variables loaded from .env
Prisma schema loaded from prisma/schema.prisma
Datasource "db": SQLite database "dev.db" at "file:./dev.db"

🚀  Your database is now in sync with your Prisma schema. Done in 15ms

✔ Generated Prisma Client (4.2.1 | library) to ./node_modules/@prisma/client in 31ms
```

```sh
# insert data
$ npx prisma db seed
Environment variables loaded from .env
Running seed command `node --require esbuild-register prisma/seed.ts` ...

🌱  The seed command has been executed.
```

## Development

From your terminal:

```sh
npm run dev
```

This starts your app in development mode, rebuilding assets on file changes.
