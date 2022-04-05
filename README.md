# Sample GraphQL project with Fastify

### Install
```shell
npm install
```

### Run
```shell
npm start
```

Then open up http://127.0.0.1:9000/graphql in your browser.

### Test queries

```shell
query Query {
  test
}
```

```shell
query Query {
  restaurants {
    id,
    name,
    rating
  },
  courses {
    name,
    priceEuro
  }
}
```