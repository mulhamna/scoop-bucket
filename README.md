# Mulhamna Scoop Bucket

Scoop manifests for Mulhamna's command-line tools on Windows.

## Packages

| Package | Description | Install |
|---|---|---|
| [jirac](https://github.com/mulhamna/jira-commands) | Fast Jira CLI and TUI built in Rust | `scoop install jirac` |
| [jirac-mcp](https://github.com/mulhamna/jira-commands) | Typed Jira MCP server built in Rust | `scoop install jirac-mcp` |
| [clickupc](https://github.com/mulhamna/clickup-commands) | Unofficial ClickUp CLI and MCP server | `scoop install clickupc` |
| [trelloc](https://github.com/mulhamna/trello-commands) | Unofficial Trello CLI and MCP server | `scoop install trelloc` |
| [broask](https://github.com/mulhamna/broask) | Plays a sound when CLI tools ask for confirmation | `scoop install broask` |
| [addx](https://github.com/mulhamna/addx) | Universal AI tooling manager with a mouse-clickable TUI | `scoop install addx` |

## Install

Add the bucket once:

```powershell
scoop bucket add mulhamna-scoop https://github.com/mulhamna/scoop-bucket
```

Install packages by name:

```powershell
scoop install jirac
scoop install jirac-mcp
scoop install clickupc
scoop install trelloc
scoop install broask
scoop install addx
```

Update Scoop and installed packages:

```powershell
scoop update
scoop update *
```

Uninstall a package:

```powershell
scoop uninstall <package>
```

Replace `<package>` with a package name such as `jirac`.
