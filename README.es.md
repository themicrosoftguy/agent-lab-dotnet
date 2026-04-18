<!-- l10n-sync: source-file="README.md" -->
# 🎯 Soc Ops — Social Bingo

> **¡Rompe el hielo, haz conexiones, gana en el networking!**

Soc Ops es un juego interactivo de bingo social construido con **Blazor WebAssembly** — diseñado para encuentros presenciales, eventos de equipo y conferencias. ¡Encuentra personas que coincidan con las preguntas, marca tu tarjeta y corre para conseguir 5 en fila!

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c6d0c33-72ec-47e8-b6bc-20837e7d830b" alt="Pantalla de inicio" width="300" />
  <img src="https://github.com/user-attachments/assets/4785afd4-c22a-4b1c-9b78-64d426c599e9" alt="Tablero de juego" width="300" />
</p>

<p align="center">
  🎮 <strong><a href="https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/">Jugar</a></strong>
  &nbsp;•&nbsp;
  📚 <strong><a href="https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/">Ver Guía del Lab</a></strong>
</p>

---

## ✨ Características

- 🎲 **Tableros aleatorios** — Cada jugador obtiene una disposición única
- 💾 **Guardado automático** — Retoma donde lo dejaste
- 🏆 **Detección de bingo** — Detección automática de filas, columnas y diagonales
- 🎉 **Modal de celebración** — Pantalla de victoria digna de confeti
- 📱 **Mobile-first** — Funciona genial en teléfonos en eventos

---

## 🚀 Inicio Rápido

### Requisitos Previos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior

### Ejecutar Localmente

```bash
cd SocOps
dotnet run
# Abrir http://localhost:5166
```

### Compilar

```bash
cd SocOps
dotnet build
```

### Abrir en GitHub Codespaces

Después de crear tu propio repositorio desde esta plantilla:

1. Abre tu repositorio en GitHub
2. Haz clic en **Code** → **Codespaces** → **Create codespace on main**
3. Espera a que termine la configuración del devcontainer
4. Ejecuta `cd SocOps && dotnet run`

---

## 📚 Guía del Lab

Este proyecto es la base para un lab práctico con agentes de GitHub Copilot. Sigue los pasos a continuación para construir y extender el juego usando agentes de IA:

| Parte | Título |
|-------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción General & Lista Rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent |

> 📝 Las guías del lab también están disponibles en la carpeta [`workshop/es/`](workshop/es/) para lectura offline.

---

## 🛠️ Stack Tecnológico

- **Framework**: Blazor WebAssembly (.NET 10)
- **Estilos**: Utilidades CSS personalizadas (inspiradas en Tailwind)
- **Estado**: Servicios con persistencia en localStorage
- **Despliegue**: GitHub Pages via Actions

## 📁 Estructura del Proyecto

```
SocOps/
├── Components/     # BingoBoard, BingoSquare, Modals
├── Models/         # Modelos de estado & datos
├── Services/       # Lógica del juego & gestión de estado
├── Data/           # Banco de preguntas
└── wwwroot/        # Recursos estáticos
```

## 🚢 Despliegue

Se despliega automáticamente en GitHub Pages al hacer push a `main`:
- Tu juego: `https://{usuario}.github.io/{nombre-repo}`

## 📝 Licencia

MIT — ¡úsalo en tu próximo evento!
