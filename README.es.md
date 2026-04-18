<!-- l10n-sync: source-file="README.md" -->
🌐 [English](README.md) | [Português (BR)](README.pt_BR.md)

<div align="center">

# 🎲 Soc Ops

### Un laboratorio práctico de agentes de IA construido alrededor de un juego de Social Bingo

*Usa el VS Code Agent Mode + GitHub Copilot para rediseñar la UI, crear agentes personalizados y desarrollar funcionalidades con TDD — todo en aproximadamente una hora.*

[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WebAssembly](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![GitHub Copilot](https://img.shields.io/badge/GitHub-Copilot-000000?logo=github)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**[🎮 Jugar](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) &nbsp;•&nbsp; [📚 Ver Guía del Lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) &nbsp;•&nbsp; [🚀 Abrir en Codespaces](#abrir-en-github-codespaces)**

</div>

---

## 🤔 ¿Qué es esto?

**Soc Ops** es un juego interactivo de Social Bingo para encuentros presenciales — ¡encuentra personas que coincidan con las preguntas y consigue 5 en fila! Pero también es el punto de partida de un taller guiado donde experimentarás el desarrollo asistido por IA en la práctica.

Al final del lab habrás:

- ✅ Usado **ingeniería de contexto** para que Copilot entienda de verdad tu código
- ✅ Diseñado una UI pulida con **desarrollo Design-First** impulsado por IA
- ✅ Creado un **agente quiz-master personalizado** que genera cartones de bingo bajo demanda
- ✅ Entregado una funcionalidad de principio a fin usando **TDD multi-agente**

---

## 🎯 Lo que aprenderás

| # | Habilidad | Descripción |
|---|-----------|-------------|
| 1 | **Ingeniería de Contexto** | Enseña a la IA sobre tu código con `.github/copilot-instructions.md` y archivos de agente personalizados |
| 2 | **Primitivas Agénticas** | Trabaja con agentes en segundo plano, agentes en la nube y flujos automatizados |
| 3 | **Desarrollo Design-First** | Deja que la IA itere en la UI mientras tú mantienes la dirección creativa |
| 4 | **Desarrollo Orientado a Pruebas** | Usa agentes especializados de TDD para un desarrollo confiable y orientado a pruebas |

---

## 🛠️ Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Runtime | .NET 10 |
| Framework de UI | Blazor WebAssembly |
| Tooling de IA | GitHub Copilot (VS Code Agent Mode) |
| Hospedaje | GitHub Pages |

---

## 📚 Guía del Lab

> **Duración:** ~1 hora &nbsp;|&nbsp; **Nivel:** Intermedio

| Parte | Título | Tiempo |
|-------|--------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción General & Lista Rápida | 5 min |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent | 20 min |

> 📝 ¿Prefieres leer sin conexión? Todas las guías están en la carpeta [`workshop/es/`](workshop/es/).

---

## ⚡ Inicio Rápido

### Requisitos Previos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior
- VS Code v1.107+ con GitHub Copilot (Pro, Business o Enterprise)

### Ejecutar localmente

```bash
cd SocOps
dotnet run
```

### Compilar

```bash
cd SocOps
dotnet build
```

### Abrir en GitHub Codespaces

El repositorio incluye un DevContainer para un entorno listo para usar:

1. Haz clic en **Use this template** → **Create a new repository**
2. En tu nuevo repositorio, haz clic en **Code** → **Codespaces** → **Create codespace on main**
3. Espera a que el contenedor termine la configuración y ejecuta:
   ```bash
   cd SocOps
   dotnet run
   ```

> 🚀 El juego se publica automáticamente en GitHub Pages con cada push a `main`.
