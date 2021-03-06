# monte-first-app

> A GitHub App built with [Probot](https://github.com/probot/probot) that Monte&#x27;s first app

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
docker build -t monte-first-app .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> monte-first-app
```

## Contributing

If you have suggestions for how monte-first-app could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Monte <miscellaneous793@gmail.com>
