# mnemnk-api

`mnemnk-api` is a [Mnemnk](https://github.com/mnemnk/mnemnk-app/) agent, which works as API server.

## Installation

1. Create a directory named `mnemnk-api` under `${mnemnk_dir}/agents/`. `${mnemnk_dir}` is the directory specified in the Mnemnk App settings, and the `agents` directory should already be automatically created.
2. Download the binary from the release page and place it under the newly created `mnemnk-api` directory. When doing so, remove the suffix like `-v0.3.0-macos-arm64` or `-v0.3.0-win-amd64` from the file name, and rename it to `mnemnk-api` for mac or `mnemnk-api.exe` for Windows.
3. Download `mnemnk.json`, and place it in the same `mnemnk-api` directory.

After installation, restart Mnemnk and `API` should be appear in Agents page.

## License

MIT
