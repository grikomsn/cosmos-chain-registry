# cosmos-chain-registry

API and static mirror for [cosmos/chain-registry](https://github.com/cosmos/chain-registry) ⛓

- [Endpoints](#endpoints)
  - [Static Mirror](#static-mirror)
  - [API](#api)
- [Examples](#examples)
- [License](#license)

## Endpoints

### Static Mirror

Static mirror is deployed using GitHub Pages at https://static.registry.cosmos.griko.id

### API

API is deployed using Vercel with rewrites at https://registry.cosmos.griko.id. For example, this URL:

```md
https://registry.cosmos.griko.id/juno
```

will rewrite to:

```md
https://static.registry.cosmos.griko.id/juno/chain.json
```

## Examples

- https://registry.cosmos.griko.id/juno
- https://registry.cosmos.griko.id/juno/chain
- https://registry.cosmos.griko.id/juno/assetlist

## License

[MIT License, Copyright (c) 2022 Griko Nibras](./LICENSE)
