<!-- <h1 align="center">Welcome to Use My Tech Stuff 👋</h1> -->
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-ff69b4.svg?cacheSeconds=2592000" />
  <img alt="License" src="https://img.shields.io/badge/license-MIT-green.svg">
  <img alt="License" src="https://img.shields.io/github/followers/jamiegoodnight?label=Follow&style=social">
</p>

![Use My Tech Stuff](https://i.imgur.com/Oyoy2ED.png)

> Node server with Express framework for Use My Tech Stuff—an app for sharing and lending tech!

## Install

```sh
npm i
```

## Dependencies

```sh
npm i express
npm i sqlite3
npm i bcryptjs
npm i cors
npm i helmet
npm i jsonwebtoken
npm i knex
npm i knex-cleaner
npm i pg
npm i cross-env
npm i dotenv
npm i nodemon --dev
npm i jest --dev
npm i supertest --dev
```

## Author

👤 **Jamie Goodnight**

- Github: [@jamiegoodnight](https://github.com/jamiegoodnight)

- Linkedin: [jamie-goodnight](www.linkedin.com/in/jamie-goodnight-54319b180)

## Show your support

Give a ⭐️ if this project helped you!

## Endpoints

| Method | Endpoint              | Requires                        | Description                                                             |
| ------ | --------------------- | ------------------------------- | ----------------------------------------------------------------------- |
| POST   | `/api/auth/register/` | `username`, `password`, `email` | Used for adding a new user to database.                                 |
| POST   | `/api/auth/login/`    | `username`, `password`          | Used to log a user in. Returns a token and the user's name in its body. |
| GET    | `/api/users`          | Successful Login                | Used to show all users in the database.                                 |
| GET    | `/api/users/:id/`     | Successful Login                | Used to show a specific user in the database.                           |
| GET    | `/api/tech`           | Successful Login                | Used to show tech in the database.                                      |
| GET    | `/api/tech/:id/`      | Successful Login                | Used to show a specific piece of tech in the database.                  |
| POST   | `/api/tech/`          | Successful Login, Data          | Used to post a new piece of tech to the database.                       |
| PUT    | `/api/tech/:id`       | Successful Login, Data          | Used to edit the logged in user's tech.                                 |
| POST   | `/api/tech/:id`       | Successful Login, Data          | Used to post a comment on the specific piece of tech.                   |
| DELETE | `/api/tech/:id/`      | Successful Login                | Used to delete the logged in user's tech.                               |

---

_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
