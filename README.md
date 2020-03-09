# TodoAppWithApolloClient
Client: React.js with ApolloClient  &amp;&amp;  Server: ApolloServer :metal: :)

## Get started

**Clone the repository:**

```sh
git clone https://github.com/ffcabbar/react-apollo-client-and-server-todoapp.git
```

**Install dependencies and run the app:**

```sh
cd server
yarn install # or npm install
yarn start   # or npm start
🌠
cd client
yarn install # or npm install
yarn start   # or npm start
```

## Testing

Open your browser at [http://localhost:5555](http://localhost:5555) and start sending queries.

**Query:**

```graphql
query {
  todos {
    text
    id
    completed
  }
}
```

The server returns the following response:

```json
{
  "data": {
    "todos": [
      {
        "text": "Hello from GraphQL",
        "id": "1583752618984",
        "completed": true
      },
      {
        "text": "react",
        "id": "1583752700115",
        "completed": true
      },
      {
        "text": "graphql",
        "id": "1583752704968",
        "completed": false
      }
    ]
  }
}
```

## Playground

![play](https://user-images.githubusercontent.com/34713212/76208621-1ab11380-6211-11ea-9d75-6744b678e59a.png)


