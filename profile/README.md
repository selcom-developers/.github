# Selcom Developers

Community-maintained, open-source clients for the [Selcom](https://www.selcom.net) payment API gateway in Tanzania.

Documentation and the shared spec: **[selcom-developers.github.io](https://selcom-developers.github.io/)**

This organization is not operated by Selcom Paytech Ltd. For API credentials, onboarding and account questions, contact Selcom through the [developer portal](https://developers.selcommobile.com/).

## Clients

Every client is built from one shared specification and checked against the same test vectors, so signing, results and webhook handling behave the same in every language.

| Project | Language | What it is |
|---|---|---|
| [selcom4j](https://github.com/selcom-developers/selcom4j) | Java 17+ | Client for the Selcom API gateway: signing, checkout, payouts, webhooks |
| [node-selcom](https://github.com/selcom-developers/node-selcom) | TypeScript / Node.js 20+ | Client with zero runtime dependencies, ESM and CommonJS |
| [selcom-php](https://github.com/selcom-developers/selcom-php) | PHP 8.2+ | Framework-agnostic client over PSR-18 |
| [laravel-selcom](https://github.com/selcom-developers/laravel-selcom) | Laravel 12 / 13 | Laravel package on the PHP client: config, webhooks, events, reconciliation |
| [selcompy](https://github.com/selcom-developers/selcompy) | Python 3.10+ | Sync and async client on httpx |
| [selcom-spec](https://github.com/selcom-developers/selcom-spec) | Specification | Signing rules, API notes and the shared test vectors |

All projects are Apache-2.0 licensed.

## Official resources

- [Selcom developer portal](https://developers.selcommobile.com/): the API reference for utility payments, wallet cash-in, checkout, C2B collection, Qwiksend, virtual cards and international transfers
- [selcompaytechltd](https://github.com/selcompaytechltd): Selcom's official client libraries for PHP, Node.js, Python, Java and C#

## Other community libraries

- PHP / Laravel: [bryceandy/laravel-selcom](https://github.com/bryceandy/laravel-selcom)
- Go: [Golang-Tanzania/selcompay-client](https://github.com/Golang-Tanzania/selcompay-client)
- Dart / Flutter: [kaykhahima/dart_selcom](https://github.com/kaykhahima/dart_selcom)

## Contributing

Issues and pull requests are welcome on every client. Changes to shared behaviour start in [selcom-spec](https://github.com/selcom-developers/selcom-spec), so all clients stay in step. To report a security issue, use each repository's private vulnerability reporting rather than a public issue. For questions about the Selcom API itself, the developer portal and Selcom support are the right place.
