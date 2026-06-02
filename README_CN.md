<div align="center">

  <img src="./Realtek_Symbol_SVG.svg" alt="Ameba-AIoT Plugins" />

  <h3>Realtek Ameba IoT SDK 的 Claude Code 完整体验 — 一键安装技能与 MCP</h3>

  <p>
    <a href="./LICENSE">
      <img src="https://img.shields.io/github/license/Ameba-AIoT/ameba-plugin-marketplace?style=flat-square" alt="License" />
    </a>
    <a href="https://github.com/Ameba-AIoT/ameba-plugin-marketplace/stargazers">
      <img src="https://img.shields.io/github/stars/Ameba-AIoT/ameba-plugin-marketplace?style=flat-square&color=0078af" alt="Stars" />
    </a>
    <img src="https://img.shields.io/badge/Claude_Code-插件支持-8A2BE2?style=flat-square" alt="Claude Code 插件" />
    <img src="https://img.shields.io/badge/MCP-realmcu--ask--ai--docs-0078af?style=flat-square" alt="MCP 服务器" />
    <img src="https://img.shields.io/badge/瑞昱_Ameba-RTL8730E_%7C_RTL8721F_%7C_更多-0078af?style=flat-square" alt="瑞昱 Ameba 芯片" />
  </p>

  <a href="./README.md">English</a>
  |
  简体中文
  |
  <a href="https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues">反馈问题</a>

</div>

> **不使用 Claude Code？** 请改用 `npx skills add https://github.com/Ameba-AIoT/skills` — 适用于 Cursor、Windsurf、Codex 等所有 AI 工具。

---

## ⚡ 快速安装

```
/plugin marketplace add https://github.com/Ameba-AIoT/ameba-plugin-marketplace
/plugin install ameba-rtos-dev@ameba-aiot
```

安装完成后获得：

- **2 个技能** 自动加载：`ameba-rtos-overview`、`ameba-quickstart-rmesh`
- **1 个 MCP 服务器** 自动注册：`realmcu-ask-ai-docs`（瑞昱在线文档查询，远程 HTTP）

---

## 📦 插件内容

### `ameba-rtos-dev`

| 技能 | 触发场景 |
|------|---------|
| `ameba-rtos-overview` | 提及 RTL8730E / RTL8721F / RTL8726E / RTL8720E / RTL8710E / RTL8713E / RTL8721Dx、`ameba-rtos`、`ameba SDK`，或编译 / 烧录 / 监控 / 调试相关任务 |
| `ameba-quickstart-rmesh` | R-MESH、`wifi_rpp`、Wi-Fi mesh 组网、`rmesh setup`、`wtn_en`、BLE 配网 |

---

## 🔧 前置条件

| 要求 | 说明 |
|------|------|
| `realmcu-ask-ai-docs` MCP | 首次使用需完成一次 GitHub OAuth 授权。安装后运行 `/mcp`，若状态显示 `△ needs authentication`，按提示操作即可。 |

---

## 💻 支持的芯片

RTL8730E · RTL8721F · RTL8726E · RTL8720E · RTL8710E · RTL8713E · RTL8721Dx

---

## 🐛 问题 & 贡献

[提交 Issue](https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues) 报告 Bug 或提出功能请求。
