# NestJS CRUD API

> Simple NestJS CRUD API with authorization

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Setup](#setup)
- [Running the app](#running-the-app)
- [Project Status](#project-status)
- [Acknowledgements](#acknowledgements)

## General Information

- I made this project to learn NestJS APIs.

## Technologies Used

- [NestJS](https://nestjs.com/)
- [Prisma](https://www.prisma.io/)
- [Jest](https://jestjs.io/)

## Features

List the ready features here:

- Signup
- Signin
- Get user data
- Edit user data
- Create bookmark
- Get bookmark by id
- Get bookmarks
- Edit bookmark
- Delete bookmark

## Setup

```bash
$ yarn install
```

#### Running the app

```bash
# development (localhost:3333)
$ yarn run db:dev:up
$ yarn run prisma:dev:deploy
$ yarn run start
``` 

```bash
# run tests
$ yarn run db:test:up
$ yarn run prisma:test:deploy
$ yarn run test:e2e
```

```bash
# prisma studio
$ npx prisma studio
```

## Project Status

Project is: _done_.

## Acknowledgements

- This project was based on [Freecodecamp tutorial](https://www.youtube.com/watch?v=GHTA143_b-s)
