<div align="center">

  <img src="./Realtek_Symbol_SVG.svg" alt="Ameba-AIoT Plugins" />

  <h3>Full Claude Code experience for Realtek Ameba IoT SDK — skills + MCP in one install</h3>

  <p>
    <a href="./LICENSE">
      <img src="https://img.shields.io/github/license/Ameba-AIoT/ameba-plugin-marketplace?style=flat-square" alt="License" />
    </a>
    <a href="https://github.com/Ameba-AIoT/ameba-plugin-marketplace/stargazers">
      <img src="https://img.shields.io/github/stars/Ameba-AIoT/ameba-plugin-marketplace?style=flat-square&color=0078af" alt="Stars" />
    </a>
    <img src="https://img.shields.io/badge/Claude_Code-plugin_ready-8A2BE2?style=flat-square" alt="Claude Code plugin" />
    <img src="https://img.shields.io/badge/MCP-realmcu--ask--ai--docs-0078af?style=flat-square" alt="MCP server" />
    <img src="https://img.shields.io/badge/Realtek_Ameba-RTL8730E_%7C_RTL8721F_%7C_more-0078af?style=flat-square" alt="Realtek Ameba chips" />
  </p>

  <a href="./README.md">English</a>
  |
  <a href="./README_CN.md">简体中文</a>
  |
  <a href="https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues">Issues</a>

</div>

> **Not using Claude Code?** Use `npx skills add https://github.com/Ameba-AIoT/skills` instead — works with Cursor, Windsurf, Codex, and other AI tools.

---

## ⚡ Quick Install

```
/plugin marketplace add https://github.com/Ameba-AIoT/ameba-plugin-marketplace
/plugin install ameba-rtos-dev@ameba-aiot
```

After installation you get:

- **2 skills** auto-loaded: `ameba-rtos-overview`, `ameba-quickstart-rmesh`
- **1 MCP server** auto-registered: `realmcu-ask-ai-docs` (Realtek documentation query, remote HTTP)

---

## 📦 Available Plugin

### `ameba-rtos-dev`

| Skill | Triggers on |
|-------|-------------|
| `ameba-rtos-overview` | Any mention of RTL8730E / RTL8721F / RTL8726E / RTL8720E / RTL8710E / RTL8713E / RTL8721Dx, `ameba-rtos`, `ameba SDK`, build / flash / monitor / debug tasks |
| `ameba-quickstart-rmesh` | R-MESH, `wifi_rpp`, Wi-Fi mesh networking, `rmesh setup`, `wtn_en`, BLE provisioning |

---

## 🔧 Prerequisites

| Requirement | Details |
|-------------|---------|
| `realmcu-ask-ai-docs` MCP | One-time GitHub OAuth. After install, run `/mcp` — if status shows `△ needs authentication`, follow the prompt. |

---

## 💻 Supported Chips

RTL8730E · RTL8721F · RTL8726E · RTL8720E · RTL8710E · RTL8713E · RTL8721Dx

---

## 🐛 Issues & Contributing

[Open an issue](https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues) for bug reports or feature requests.
