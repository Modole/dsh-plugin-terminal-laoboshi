# 终端 · 劳博士 DSH 插件

为劳博士 DSH 桌面客户端提供多标签本地终端与 tmux 会话。

> 当前 v0.1.0 的交互界面依赖劳博士 Desktop 提供的原生宿主桥接；在普通 DSH Web 中会显示兼容性提示。

## 安装

```bash
dsh plugin --profile web add https://github.com/Modole/dsh-plugin-terminal-laoboshi.git
```

安装后重启 `dsh web`。DSH 会读取 `dsh.bundle` manifest，并自动把本插件加入当前 profile。

## 来源与作者

本插件从 [劳博士 Agent Studio](https://github.com/Modole/laobos-agent-studio) 的内置能力独立整理而来。作者：Modole。

## 安全

插件代码以当前用户权限运行。安装前请审阅源码；不要把密钥、SSH 私钥或本机运行数据库提交到 Issue。

## 许可证

MIT
