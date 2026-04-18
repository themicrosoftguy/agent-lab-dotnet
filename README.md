🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### A hands-on AI agent lab built around a Social Bingo game

*Use VS Code Agent Mode + GitHub Copilot to redesign UI, create custom agents, and build features with TDD — all in about an hour.*

[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WebAssembly](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![GitHub Copilot](https://img.shields.io/badge/GitHub-Copilot-000000?logo=github)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**[🎮 Play the Game](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) &nbsp;•&nbsp; [📚 View Lab Guide](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) &nbsp;•&nbsp; [🚀 Open in Codespaces](#open-in-github-codespaces)**

</div>

---

## 🤔 What is this?

**Soc Ops** is an interactive Social Bingo game for in-person mixers — find people who match the prompts and get 5 in a row! But it's also the starting point for a guided workshop where you'll experience real-world AI-assisted development.

By the end of the lab you will have:

- ✅ Used **context engineering** to make Copilot truly understand your codebase
- ✅ Designed a polished UI with **Design-First development** driven by AI
- ✅ Built a **custom quiz-master agent** that generates bingo cards on demand
- ✅ Shipped a new feature end-to-end using **multi-agent TDD**

---

## 🎯 What You'll Learn

| # | Skill | Description |
|---|-------|-------------|
| 1 | **Context Engineering** | Teach the AI about your codebase with `.github/copilot-instructions.md` and custom agent files |
| 2 | **Agentic Primitives** | Work with background agents, cloud agents, and automated workflows |
| 3 | **Design-First Development** | Let AI iterate on UI while you stay in the creative director seat |
| 4 | **Test-Driven Development** | Use specialized TDD agents for reliable, test-first feature work |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Runtime | .NET 10 |
| UI Framework | Blazor WebAssembly |
| AI Tooling | GitHub Copilot (VS Code Agent Mode) |
| Hosting | GitHub Pages |

---

## 📚 Lab Guide

> **Duration:** ~1 hour &nbsp;|&nbsp; **Level:** Intermediate

| Part | Title | Time |
|------|-------|------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | 5 min |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min |

> 📝 Prefer offline reading? All guides are mirrored in the [`workshop/`](workshop/) folder.

---

## ⚡ Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher
- VS Code v1.107+ with GitHub Copilot (Pro, Business, or Enterprise)

### Run locally

```bash
cd SocOps
dotnet run
```

### Build

```bash
cd SocOps
dotnet build
```

### Open in GitHub Codespaces

The repo ships with a DevContainer for a zero-config environment:

1. Click **Use this template** → **Create a new repository**
2. On your new repo, click **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the container to finish setup, then run:
   ```bash
   cd SocOps
   dotnet run
   ```

> 🚀 The game deploys automatically to GitHub Pages on every push to `main`.
