# Railway Template

[Exograph](https://exograph.dev) is a way to build fast, flexible, secure GraphQL backends in minutes!

This template provisions a Postgres database and an Exograph server connected to it.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/eMpJru?referralCode=tKfnpw)

## Getting Started

Click the "Deploy on Railway" button!

## Playing with the API

Install Exograph following the [Getting Started](https://exograph.dev/docs/getting-started) guide.

Then, run the following command to start the server:

```bash
exo playground --endpoint <server-url>/graphql
```

Then you can execute mutations like:

```graphql
mutation {
  createTodo(data: { title: "Deploy Exograph to Railway", completed: true }) {
    id
  }
}
```

And queries like:

```graphql
query {
  todos {
    id
    title
    completed
  }
}
```
