# coding-session-plugin

Claude Code 插件 - D:\projects 项目编程会话管理。

## 功能

跟踪项目编程历史，记录文件修改、函数变更和原因。

## 安装

```bash
claude plugin marketplace add COLORFUL/coding-session-plugin
claude plugin install coding-session
```

## 命令

| 命令 | 功能 |
|------|------|
| `/coding-session:start [项目名]` | 启动项目编程会话 |
| `/coding-session:end` | 保存修改记录 |
| `/coding-session:list` | 列出所有项目 |

## 项目结构

```
D:\projects\
├── JobHunter\
├── math-tutor-demo\
├── math-tutor-video\
├── obsidian-knowledge-base\
└── video-analyzer\
```

## 记录存储

修改记录自动保存到：`C:\Users\COLORFUL\.claude\PROJECT_LOG.md`
