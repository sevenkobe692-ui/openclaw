# OpenClaw 🤖

**下一代 AI 助手平台 | Next-Gen AI Assistant Platform**

---

## 📖 项目简介

OpenClaw 是一个功能强大的 AI 助手平台，支持多会话管理、子代理编排、定时任务、消息集成等高级功能。

## ✨ 核心特性

- 🎯 **多会话管理** - 同时运行多个独立会话
- 🤖 **子代理系统** -  spawn 子代理处理专项任务
- ⏰ **定时任务** - Cron 作业和提醒系统
- 💬 **消息集成** - Telegram/WhatsApp/Discord 等多平台支持
- 🧠 **记忆系统** - 持久化记忆和上下文管理
- 🔧 **技能系统** - 可扩展的技能市场
- 🌐 **浏览器自动化** - 网页操作和爬取
- 📊 **GitHub 集成** - Issue/PR 管理、CI 状态监控

## 🚀 快速开始

### 环境要求

- Node.js 18+
- 各平台 API Key（根据使用需求）

### 安装

```bash
# 全局安装
npm install -g openclaw

# 初始化工作区
openclaw init

# 启动网关
openclaw gateway start

# 查看状态
openclaw status
```

### 配置

编辑 `~/.openclaw/config.json` 添加你的 API Keys：

```json
{
  "models": {
    "default": "your-model"
  },
  "channels": {
    "telegram": {
      "botToken": "YOUR_BOT_TOKEN"
    }
  }
}
```

## 📁 工作区结构

```
~/.openclaw/workspace/
├── SOUL.md          # AI 人格定义
├── USER.md          # 用户信息
├── MEMORY.md        # 长期记忆
├── TOOLS.md         # 工具配置
├── HEARTBEAT.md     # 心跳任务
├── memory/          # 每日记忆日志
└── skills/          # 自定义技能
```

## 🛠️ 内置技能

| 技能 | 描述 |
|------|------|
| github | GitHub Issue/PR 管理 |
| weather | 天气查询 |
| web_search | 网络搜索 |
| browser | 浏览器自动化 |
| tavily | AI 优化搜索 |
| summarize | 内容摘要 |
| ... | 更多技能持续添加 |

## 🔌 消息平台支持

- ✅ Telegram
- ✅ WhatsApp
- ✅ Discord
- ✅ Slack
- ✅ Signal
- ✅ iMessage
- ✅ IRC

## 📖 文档

- 📘 [官方文档](https://docs.openclaw.ai)
- 💬 [Discord 社区](https://discord.com/invite/clawd)
- 🛒 [技能市场](https://clawhub.com)

## 🤝 贡献

欢迎贡献代码、技能或文档！

```bash
# Fork 项目
git fork sevenkobe692-ui/openclaw

# 创建分支
git checkout -b feature/your-feature

# 提交代码
git commit -m "feat: add your feature"

# 推送并创建 PR
git push origin feature/your-feature
```

## 📄 许可证

MIT License

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sevenkobe692-ui/openclaw&type=Date)](https://star-history.com/#sevenkobe692-ui/openclaw&Date)

---

**🙏 感谢使用 OpenClaw！**

*Built with ❤️ by sevenkobe692-ui*

**🌟 如果这个项目对你有帮助，请给个 Star！**
