# cosmos-chain-registry

Statically deployed Cosmos chain registry ⛓

## Endpoints

- API: https://registry.cosmos.griko.dev
- Static: https://static.registry.cosmos.griko.dev

Static URL is deployed using GitHub Pages, while API URL is deployed using Vercel with rewrites, for example:

```md
registry.cosmos.griko.dev/juno
```

will rewrite to:

```md
static.registry.cosmos.griko.dev/juno/chain.json
```

## Examples

- https://registry.cosmos.griko.dev/juno
- https://registry.cosmos.griko.dev/juno/chain
- https://registry.cosmos.griko.dev/juno/assetlist

## License

[MIT License, Copyright (c) 2022 Griko Nibras](./LICENSE)
