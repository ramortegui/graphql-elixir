# Community


This is the an application sample based on the howtographql using elixir and absinthe library.

To start your Phoenix server:

  * Install dependencies with `mix deps.get`
  * Create and migrate your database with `mix ecto.setup`
  * Start Phoenix endpoint with `mix phx.server`

Now you can visit [`localhost:4000/graphiql`](http://localhost:4000/graphiql) from your browser.


## Query sample:
    {
      allLinks {
        id
        url
        description
      }
    }

## Mutation sample:
    mutation {
      createLink(
        url: "http://npmjs.com/package/graphql-tools",
        description: "Best Tools!",
      ) {
        id
        url
        description
      }
    }

## Learn more

  * Graphql-elixir Tutorial: https://www.howtographql.com/graphql-elixir/0-introduction/
