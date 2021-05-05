# About the MyFDWeb API

We are currently trying to build most of our websites as [Jamstack](https://jamstack.org/) apps.
Meaning that not only those, but also other services and maybe one day even user integrations can use our different api endpoints in order to interact with our data.

Most of these endpoints are, as indicated above, for managing data. So you might think of a REST API first.
But we decided to choose a modern alternative and built them as [GraphQL](https://graphql.org/) APIs.

If you know nothing about GraphQL, but want to work with our APIs, I suggest reading the [introduction to GraphQL](https://graphql.org/learn/) first.

## GraphQL Schema

In most cases you find the GraphQL schema lying right next to the API, as a file `schema.graphql`.
For example:

GraphQL API Endpoint:
`https://api.myfdweb.de/graphql`
	
GraphQL Schema File:
`https://api.myfdweb.de/schema.graphql`

## Bugs

If you find any bugs and are willing to share them with us, feel free to contact [me](https://fdhoho007.de/) via Discord or send me an email: [bugs@fdhoho007.de](mailto:bugs@fdhoho007.de)