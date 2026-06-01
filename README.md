# Ameba IoT SDK — Claude Code Plugin Marketplace

Claude Code plugin marketplace for Realtek Ameba IoT SDK development. Installs AI skills **and** MCP servers in one step.

> **Not using Claude Code?** Get the raw skill files from [Ameba-AIoT/skills](https://github.com/Ameba-AIoT/skills) instead.

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
| `AMEBA_SDK_ROOT` *(optional)* | Only needed for local SDK build / flash features. Set before starting Claude Code: `export AMEBA_SDK_ROOT=<absolute path to your SDK>`. Other features are unaffected if unset. |

---

## Supported Chips

RTL8730E · RTL8721F · RTL8726E · RTL8720E · RTL8710E · RTL8713E · RTL8721Dx

---

## Issues & Contributing

[Open an issue](https://github.com/Ameba-AIoT/ameba-plugin-marketplace/issues) for bug reports or feature requests.
