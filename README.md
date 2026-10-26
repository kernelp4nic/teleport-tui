# teleport-tui

Terminal UI to browse, filter and connect to Teleport hosts.

Requires the Teleport client (`tsh`) and an active session, or run `ctrl-l` inside the app to log in.

## Install

```sh
brew install kernelp4nic/tap/teleport-tui
```

## Config

`~/.config/teleport-tui/config`:

```
proxy = teleport.example.com:443
user = you
op-item = Teleport   # 1Password item for autofill (needs the op CLI)
```

## Release

Push a tag like `v0.2.0` to run the tests and bump the Homebrew formula in `kernelp4nic/homebrew-tap`
(needs the `TAP_GITHUB_TOKEN` repo secret).
