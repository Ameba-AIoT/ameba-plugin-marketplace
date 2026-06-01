# Ameba IoT SDK — Claude Code Plugin Marketplace

Full Claude Code experience for Realtek Ameba IoT SDK development — installs AI skills **and** MCP servers in one step.

> **Not using Claude Code?** Use `npx skills add Ameba-AIoT/skills` instead — works with Cursor, Windsurf, Codex, and other AI tools.

---

## Quick Install

```
/plugin marketplace add https://github.com/Ameba-AIoT/ameba-plugin-marketplace
/plugin install ameba-rtos-dev@ameba-aiot
```

After installation you get:

- **2 skills** auto-loaded: `ameba-rtos-overview`, `ameba-quickstart-rmesh`
- **1 MCP server** auto-registered: `realmcu-ask-ai-docs` (Realtek documentation query, remote HTTP)

---

## Available Plugin

### `ameba-rtos-dev`

| Skill | Triggers on |
|-------|-------------|
| `ameba-rtos-overview` | Any mention of RTL8730E / RTL8721F / RTL8726E / RTL8720E / RTL8710E / RTL8713E / RTL8721Dx, `ameba-rtos`, `ameba SDK`, build / flash / monitor / debug tasks |
| `ameba-quickstart-rmesh` | R-MESH, `wifi_rpp`, Wi-Fi mesh networking, `rmesh setup`, `wtn_en`, BLE provisioning |

---

## Prerequisites

| Requirement | Details |
|-------------|---------|
| `realmcu-ask-ai-docs` MCP | One-time GitHub OAuth. After install, run `/mcp` — if status shows `△ needs authentication`, follow the prompt. |

---

## Supported Chips

RTL8730E · RTL8721F · RTL8726E · RTL8720E · RTL8710E · RTL8713E · RTL8721Dx

---

## Issues & Contributing

[Open an issue](https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues) for bug reports or feature requests.
