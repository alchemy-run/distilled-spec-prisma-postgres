# distilled-spec-prisma-postgres

A git mirror of the Prisma Postgres [Management API spec](https://api.prisma.io/v1/doc). The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-prisma-postgres.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
