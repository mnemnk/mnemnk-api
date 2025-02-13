# mnemnk-api

`mnemnk-api` is a [Mnemnk](https://github.com/mnemnk/mnemnk-app/) agent, which works as API server.

## Installation

```shell
cargo install mnemnk-api
```

## Setup

`mnemnk-api` is enabled by default. After installation, restart Mnemnk and it should be running.

If it is not enabled, please edit Settings in Mnemnk as follows

```json
  "agents": {
    "api": {
      "enabled": true
    },
    ...
```

Save the settings and restart Mnemnk.

## Development

```shell
> cargo run
...
```

You can stop `mnemnk-api` by entering QUIT.

## License

MIT
