# 终端 · Laoboshi DSH Plugin

为劳博士 DSH 桌面客户端提供多标签本地终端与 tmux 会话。

> The v0.1.0 UI uses native host capabilities supplied by Laoboshi Desktop. Stock DSH Web shows a compatibility notice.

## Install

```bash
dsh plugin --profile web add github:Modole/dsh-plugin-terminal-laoboshi
```

Restart `dsh web` after installation. DSH reads the `dsh.bundle` manifest and adds this package to the selected profile.

## Origin and author

Extracted from the built-in capability in [Laoboshi Agent Studio](https://github.com/Modole/laobos-agent-studio). Author: Modole.

## Security

Plugins execute with the current user's permissions. Review the source before installation and never post credentials, SSH private keys, or local runtime databases in issues.

## License

MIT
