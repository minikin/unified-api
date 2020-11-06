# [WIP] Unified API

Based on [GOTO 2020 • GraphQL, gRPC and REST, Oh My! A Method for Unified API Design • Mike Amundsen](https://youtu.be/7Anvawx9ixY)

Install `unified-api` npm module globally

```sh
npm i -g minikin/unified-api
```

Defein your ALPS

TODO:

Generate OPEN API specs

```sh
unified-api -f company.yaml -t openapi > company-oas.yaml
```

Generate GraphQL schemas

```sh
unified-api -f company.yaml -t sdl > company-gql.sdl
```

Genarate gRPC

```sh
unified-api -f company.yaml -t proto > company-grpc.proto
```