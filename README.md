# OpenCode Launcher

Launch [OpenCode](https://opencode.ai) (v2 CLI) in a VS Code split terminal — by **Amit Narwal**.

## Prerequisites

Install the [OpenCode CLI](https://opencode.ai) (v2) and make sure `opencode` is on your `PATH`. Check with:

```sh
opencode --version
```

## Features

- **Top-right button**: click the OpenCode icon in the editor toolbar to open a new session beside your code.
- **Quick launch**: `Ctrl+Esc` (Windows/Linux) or `Cmd+Esc` (Mac) opens OpenCode, or focuses the existing session.
- **New session**: `Ctrl+Shift+Esc` (Windows/Linux) or `Cmd+Shift+Esc` (Mac) always starts a fresh terminal.
- **File context**: `Ctrl+Alt+K` (Windows/Linux) or `Cmd+Option+K` (Mac) inserts `@relative/path#Lstart-end` for the active selection into the OpenCode terminal (typed, not executed).

## Commands

| Command | Keybinding |
|---|---|
| Open OpenCode | `Ctrl+Esc` / `Cmd+Esc` |
| Open OpenCode in new tab | `Ctrl+Shift+Esc` / `Cmd+Shift+Esc` |
| Add Filepath to Terminal | `Ctrl+Alt+K` / `Cmd+Option+K` |

## Notes

- Works with the OpenCode **v2** CLI (plain `opencode` launch, no `--port` flag).
- Terminals are named `opencode`. If one already exists, "Open OpenCode" focuses it.
- Disable or uninstall the old `sst-dev.opencode` extension to avoid duplicate toolbar buttons.

## Support

Report issues at <https://github.com/amitnarw/opencode-launcher/issues>.

## Credits

Forked from the MIT-licensed `sst-dev.opencode` extension, ported to the v2 CLI. See `LICENSE` for attribution.
