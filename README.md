## NextJs + Postgres + Prisma + AuthJS Setup using Bun

```
bun create next-app my-app
cd my-app
bun run dev
```

### Shadcn Setup

Docs : [Link](https://ui.shadcn.com/docs/installation/next)

```
bunx shadcn-ui@latest init
```

### AuthJS Setup

Docs : [Link](https://authjs.dev/getting-started/installation)

```

### DB + Prisma Setup

Setup Postgres Database from [Aiven](https://aiven.io/)
Docs : [Prisma ORM](https://www.prisma.io/docs/getting-started/setup-prisma/add-to-existing-project/relational-databases-typescript-postgresql) [Prisma Accelerate](https://www.prisma.io/docs/accelerate/getting-started)
```

```
bun prisma migrate dev
bun prisma generate --no-engine
bun prisma studio
bun run dev
```
