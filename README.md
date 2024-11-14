# Monorepo with NPM

## Initialize the project

```
npm init -y
npm init -y -w packages/server -w packages/client
npm install

npm ls
```

## Install React and NestJS

```
npm create vite@latest . -w packages/client
npm create nestjs@latest . -w packages/api
```

## Dev

```
npm -w client run dev
npm -w api run start:dev
```
