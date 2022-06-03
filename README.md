# cosmos-chain-registry

API and static mirror for [cosmos/chain-registry](https://github.com/cosmos/chain-registry) ⛓

- [Endpoints](#endpoints)
  - [Static Mirror](#static-mirror)
  - [API](#api)
- [Examples](#examples)
- [License](#license)

## Endpoints

### Static Mirror

Static mirror is deployed using GitHub Pages at https://static.registry.cosmos.griko.dev

### API

API is deployed using Vercel with rewrites at https://registry.cosmos.griko.dev. For example, this URL:

```md
https://registry.cosmos.griko.dev/juno
```

will rewrite to:

```md
https://static.registry.cosmos.griko.dev/juno/chain.json
```

## Examples

- https://registry.cosmos.griko.dev/juno
- https://registry.cosmos.griko.dev/juno/chain
- https://registry.cosmos.griko.dev/juno/assetlist

## License

[MIT License, Copyright (c) 2022 Griko Nibras](./LICENSE)
