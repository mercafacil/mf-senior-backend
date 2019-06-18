# Mercafacil Senior Backend Test Project

Develop a robust server that receives GraphQL queries/mutations to record and analyze the traffic in 
multiple websites by multiple users.

Given that there are millions of users browsing millions of websites at any given minute, the server must
be resilient, fault tolerant and able to handle lots of simultaneous requests.

This project must also include a load test client configured to post mutations to the server. The client
doesn't necessarily need to be implemented in this project, since there are some other open source tools
that can perform these queries.

## GraphQL

The [GraphQL schema](./schema.graphql) defines the types, queries and mutations that need to be 
implemented to define the API.

## Technologies

Although the server can be implemented in any language (as long as it's exposed as a GraphQL endpoint),
some languages are more encouraged than others and will yield 'bonus points' if used.

Encouraged languages:
* Go
* Elixir/Erlang
* Clojure
* Python
* JavaScript/TypeScript
* ... pretty much any functional language

## Client

The load test client that post mutations to the server must be configured in this project through a npm script, bash script, etc.

There are many libraries and packages that implement GraphQL clients, some suggestions are
[easy-GraphQL-load-tester](https://github.com/EasyGraphQL/easygraphql-load-tester) and 
[graphql-request](https://github.com/prisma/graphql-request)