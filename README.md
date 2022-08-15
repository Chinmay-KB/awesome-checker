# awesome-checker

> A GitHub App built with [Probot](https://github.com/probot/probot) that A probot app which checks whether PRs submitted on awesome repos have github links which have enough stars
Test
## Setup

```sh
# Install dependencies
npm install

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t awesome-checker .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> awesome-checker
```

## Contributing

If you have suggestions for how awesome-checker could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2022 Chinmay Kabi
