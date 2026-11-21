# Contributing

Thanks for helping. These are community projects; they are not affiliated with Selcom Paytech Ltd.

## The spec is the source of truth

Signing, results and webhooks follow [selcom-spec](https://github.com/selcom-developers/selcom-spec). If a client and the spec disagree, the client is wrong, or the spec needs a fix that every client then picks up. Open the change against the spec first.

## Clean room

Write your own code. Do not copy from Selcom's official clients, from other community clients, or from any private integration. Reading public documentation for behaviour is fine.

## Pull requests

- One concern per pull request, with tests.
- Behaviour changes need a line in `CHANGELOG.md` under Unreleased.
- Changes to rules or test vectors start in selcom-spec; clients then refresh their pinned copy.
- Use neutral, factual wording in code, commits, issues and documentation.
- Use made-up test data only. Never post API keys, secrets, PINs, tokens or customer data.

Each repository may add its own build and test instructions in its own `CONTRIBUTING.md`.

## Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
