# restore-graphql-playground

This is an Apollo Server Plugin that can be used to run a GraphQL Playground in place of the Apollo Studio Sandbox.

> Note there are [security issues](https://github.com/graphql/graphql-playground/issues/1143) with GraphQL Playground so it has been retired.

### Installation

```bash
npm install --save-dev restore-graphql-playground
```

### Usage

```js
import { RestoreGraphQLPlayground } from "restore-graphql-playground";

new ApolloServer({ plugins: [RestoreGraphQLPlayground()] });
```

### License

MIT
