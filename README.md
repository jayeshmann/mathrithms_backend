# Mathrithms Backend

A simple backend test

## Dependencies

Requires: node.js [Install](https://nodejs.org)

This project uses `yarn` as it's package manager.

```bash
npm -g i yarn
```

### Install

```bash
yarn
```

## Backend

- node & express

### Endpoints

`GET` only.

- `/` - responds with `Nothing to see here!` and status `200 OK`
- `/users` - list of all users
- `/users/:id` - single user, eg. `users/1` returns details of user with id 1 if users exists, `status 404` otherwise

### Dev run

Add users data in same format to `users` in `index.js` file.

Run the backend

```bash
yarn dev
```

Server listens on port `5001`.

### Prod run

```bash
yarn start
```
