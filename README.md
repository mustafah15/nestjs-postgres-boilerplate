# NestJS Framework Boilerplate (PostgreSQL)

A local development setup or boilerplate for [Nest.js framework](https://nestjs.com/) with [PostgreSQL](https://www.postgresql.org/) and [pgAdmin4](https://www.pgadmin.org/) using [Docker Compose](https://docs.docker.com/compose/).

## Quick Start

- Clone this repo
- Install npm packages - _for IDE type checking_.

```bash
cd nestjs-postgres-boilerplate
yarn install --frozen-lockfile
```

- Build and run the Docker image for development

```bash
yarn docker-compose:dev
```

- Access the app at http://localhost:3000.
- Make file changes and it will automatically rebuild the app.

### Running All Tests

```bash
yarn docker-compose:test
```

### Build For Production

```bash
yarn docker-compose:prod
```

#### credits 
forked from [Dominic Arrojado boilerplate](https://github.com/dominicarrojado/nestjs-postgres-boilerplate).
