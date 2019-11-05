## Commit rule

See [here](https://github.com/bouteillerAlan/Commit-Rule)


## Endpoint naming rules
See [here](https://gitlab.helyx.dev/helyx-staff/archivist/api-rules/blob/master/README.md)

## Files architecture rules

Each component have a proper folder whit this own tests, module, controller, schemas, ...

Example of file architecture : 
```
- back
  |_ dist
  |_ node_modules
  |_ public
  |_ script_mongo
  |_ test
  |_ src
      |_ component_a
          |_ dto
              |_ create_component_a.dto.ts
              |_ update_component_a.dto.ts
          |_ interfaces
              |_ component_a.interfaces.ts
          |_ schemas
              |_ component_a.schemas.ts
          |_ component_a.controller.ts
          |_ component_a.module.ts
          |_ component_a.service.ts
      |_ component_b
          |_ ....     
```

## Command
### Installation

```bash
$ yarn
```

### Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod
```

### Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```
