# WEB React Ts GraphQL

WEB with React, Typescript and GraphQL.

## Get Started

Install

```bash
yarn
```

Run for Developer

```bash
yarn dev
```

Build project

```bash
yarn build
```

Format code with Prettier

```bash
yarn format
```

Lint code with ESLint

```bash
yarn lint
```

## Deploy in docker container

```bash
yarn build && docker build -t react .
```

Run container

```bash
docker run -dit -p 80:80 --name=web react
```

Go to http://localhost
