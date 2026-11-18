# nest-boilerplate

Production-grade NestJS starter I use to bootstrap new backend services. NestJS 11 + TypeScript, with the plumbing already wired.

## What's inside

- **NestJS 11 + TypeScript** on Express
- **TypeORM + PostgreSQL** (`pg`), with migration scripts and a seed runner
- **CQRS** via `@nestjs/cqrs`
- **Swagger** OpenAPI docs via `@nestjs/swagger`
- **AutoMapper** for DTO/entity mapping
- **pino** structured logging (`nestjs-pino`, pretty output in dev)
- **class-validator / class-transformer** request validation
- dotenv config, ESLint + Prettier, Jest (unit + e2e)

## Run it

```bash
yarn install
yarn start:dev        # watch mode
```

Database:

```bash
yarn migration:run    # apply migrations
yarn seed:run         # seed data
```

Other scripts: `yarn build`, `yarn start:prod`, `yarn lint`, `yarn test`, `yarn test:e2e`.
