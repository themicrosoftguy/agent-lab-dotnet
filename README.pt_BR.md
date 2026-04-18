<!-- l10n-sync: source-file="README.md" -->
🌐 [English](README.md) | [Español](README.es.md)

<div align="center">

# 🎲 Soc Ops

### Um laboratório prático de agentes de IA construído em torno de um jogo de Social Bingo

*Use o VS Code Agent Mode + GitHub Copilot para redesenhar a UI, criar agentes personalizados e desenvolver funcionalidades com TDD — tudo em cerca de uma hora.*

[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WebAssembly](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![GitHub Copilot](https://img.shields.io/badge/GitHub-Copilot-000000?logo=github)](https://github.com/features/copilot)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**[🎮 Jogar](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/) &nbsp;•&nbsp; [📚 Ver Guia do Lab](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/) &nbsp;•&nbsp; [🚀 Abrir no Codespaces](#abrir-no-github-codespaces)**

</div>

---

## 🤔 O que é isso?

**Soc Ops** é um jogo interativo de Social Bingo para encontros presenciais — encontre pessoas que correspondam às perguntas e consiga 5 em fila! Mas também é o ponto de partida de um workshop guiado onde você vai vivenciar o desenvolvimento assistido por IA na prática.

Ao final do lab você terá:

- ✅ Usado **engenharia de contexto** para fazer o Copilot realmente entender o seu código
- ✅ Projetado uma UI polida com **desenvolvimento Design-First** orientado por IA
- ✅ Criado um **agente quiz-master personalizado** que gera cartelas de bingo sob demanda
- ✅ Entregado uma funcionalidade do início ao fim usando **TDD multi-agente**

---

## 🎯 O que você vai aprender

| # | Habilidade | Descrição |
|---|-----------|-----------|
| 1 | **Engenharia de Contexto** | Ensine a IA sobre o seu código com `.github/copilot-instructions.md` e arquivos de agente personalizados |
| 2 | **Primitivas Agênticas** | Trabalhe com agentes em background, agentes na nuvem e fluxos automatizados |
| 3 | **Desenvolvimento Design-First** | Deixe a IA iterar na UI enquanto você mantém a direção criativa |
| 4 | **Desenvolvimento Orientado a Testes** | Use agentes especializados de TDD para desenvolvimento confiável e test-first |

---

## 🛠️ Stack Tecnológico

| Camada | Tecnologia |
|--------|-----------|
| Runtime | .NET 10 |
| Framework de UI | Blazor WebAssembly |
| Tooling de IA | GitHub Copilot (VS Code Agent Mode) |
| Hospedagem | GitHub Pages |

---

## 📚 Guia do Lab

> **Duração:** ~1 hora &nbsp;|&nbsp; **Nível:** Intermediário

| Parte | Título | Tempo |
|-------|--------|-------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida | 5 min |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent | 20 min |

> 📝 Prefere ler offline? Todos os guias estão espelhados na pasta [`workshop/pt_BR/`](workshop/pt_BR/).

---

## ⚡ Início Rápido

### Pré-requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior
- VS Code v1.107+ com GitHub Copilot (Pro, Business ou Enterprise)

### Executar localmente

```bash
cd SocOps
dotnet run
```

### Compilar

```bash
cd SocOps
dotnet build
```

### Abrir no GitHub Codespaces

O repositório inclui um DevContainer para um ambiente sem configuração:

1. Clique em **Use this template** → **Create a new repository**
2. No seu novo repositório, clique em **Code** → **Codespaces** → **Create codespace on main**
3. Aguarde a configuração do container e execute:
   ```bash
   cd SocOps
   dotnet run
   ```

> 🚀 O jogo é publicado automaticamente no GitHub Pages a cada push para `main`.
