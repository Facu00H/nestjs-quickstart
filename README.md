<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# NestJS Quickstart Template

<p align="center">
  A feature-rich starter template for building efficient and scalable server-side applications with NestJS.
</p>

<p align="center">
  <a href="https://github.com/your-username/your-repo-name/actions/workflows/biome.yml"><img src="https://github.com/your-username/your-repo-name/actions/workflows/biome.yml/badge.svg" alt="Biome CI" /></a>
</p>

## About This Template

This repository is a starter template for building applications with the [Nest](https://github.com/nestjs/nest) framework. It comes pre-configured with a set of essential tools to streamline your development process.

### Features

- **[NestJS](https://nestjs.com/):** A progressive Node.js framework for building efficient, reliable and scalable server-side applications.
- **[Prisma](https://www.prisma.io/):** Next-generation Node.js and TypeScript ORM.
- **[Biome](https://biomejs.dev/):** A high-performance toolchain for web development, used here for linting and formatting.
- **[Husky](https://typicode.github.io/husky/):** Modern native Git hooks made easy.
- **PNPM:** Fast, disk space-efficient package manager.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v18 or newer)
- [pnpm](https://pnpm.io/installation)

### Installation

1.  Use this repository as a template by clicking the "Use this template" button on GitHub.
2.  Clone your newly created repository:
    ```bash
    git clone https://github.com/your-username/your-new-repo.git
    ```
3.  Navigate to the project directory and install dependencies:
    ```bash
    cd your-new-repo
    pnpm install
    ```
4.  Set up your environment variables by copying the example file:
    ```bash
    cp .env.example .env
    ```
    > **Note:** Remember to fill in your database connection details in the `.env` file.

## Development

To compile and run the project in development mode:

```bash
# watch mode
$ pnpm run start:dev
```

The application will be available at `http://localhost:3000`.

### Other Scripts

```bash
# production build
$ pnpm run build

# start in production mode
$ pnpm run start:prod
```

## Testing

To run the test suites:

```bash
# unit tests
$ pnpm run test

# e2e tests
$ pnpm run test:e2e

# test coverage
$ pnpm run test:cov
```

## Deployment

When you're ready to deploy your NestJS application, refer to the official [deployment documentation](https://docs.nestjs.com/deployment) for guidance on best practices.

## License

This project is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).