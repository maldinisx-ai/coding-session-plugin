# 开始编程

启动 D:\projects 项目的编程会话。

## 用法

- `/coding-session:start` - 交互式选择项目
- `/coding-session:start [项目名]` - 直接启动指定项目

## 执行步骤

1. 扫描 `D:\projects` 目录获取所有项目
2. 如果未指定项目名，使用 AskUserQuestion 让用户选择
3. 读取项目历史记录（从 PROJECT_LOG.md）
4. 展示项目概览
5. 准备开始编程
