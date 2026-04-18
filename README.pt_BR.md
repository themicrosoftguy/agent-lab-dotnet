<!-- l10n-sync: source-file="README.md" -->
# 🎯 Soc Ops — Social Bingo

> **Quebre o gelo, faça conexões, vença no networking!**

Soc Ops é um jogo interativo de bingo social construído com **Blazor WebAssembly** — projetado para encontros presenciais, eventos de equipe e conferências. Encontre pessoas que correspondam às perguntas, marque sua cartela e corra para conseguir 5 em uma fileira!

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c6d0c33-72ec-47e8-b6bc-20837e7d830b" alt="Tela inicial" width="300" />
  <img src="https://github.com/user-attachments/assets/4785afd4-c22a-4b1c-9b78-64d426c599e9" alt="Tabuleiro do jogo" width="300" />
</p>

<p align="center">
  🎮 <strong><a href="https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/">Jogar</a></strong>
  &nbsp;•&nbsp;
  📚 <strong><a href="https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/">Ver Guia do Lab</a></strong>
</p>

---

## ✨ Funcionalidades

- 🎲 **Tabuleiros aleatórios** — Cada jogador recebe uma disposição única
- 💾 **Salvamento automático** — Continue de onde parou
- 🏆 **Detecção de bingo** — Detecção automática de linhas, colunas e diagonais
- 🎉 **Modal de celebração** — Tela de vitória digna de confete
- 📱 **Mobile-first** — Funciona muito bem em celulares em eventos

---

## 🚀 Início Rápido

### Pré-requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior

### Executar Localmente

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

### Abrir no GitHub Codespaces

Após criar seu próprio repositório a partir deste template:

1. Abra seu repositório no GitHub
2. Clique em **Code** → **Codespaces** → **Create codespace on main**
3. Aguarde a configuração do devcontainer terminar
4. Execute `cd SocOps && dotnet run`

---

## 📚 Guia do Lab

Este projeto é a base para um lab prático com agentes do GitHub Copilot. Siga os passos abaixo para construir e estender o jogo usando agentes de IA:

| Parte | Título |
|-------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent |

> 📝 Os guias do lab também estão disponíveis na pasta [`workshop/pt_BR/`](workshop/pt_BR/) para leitura offline.

---

## 🛠️ Stack Tecnológica

- **Framework**: Blazor WebAssembly (.NET 10)
- **Estilização**: Utilitários CSS personalizados (inspirados no Tailwind)
- **Estado**: Serviços com persistência em localStorage
- **Deploy**: GitHub Pages via Actions

## 📁 Estrutura do Projeto

```
SocOps/
├── Components/     # BingoBoard, BingoSquare, Modals
├── Models/         # Modelos de estado & dados
├── Services/       # Lógica do jogo & gerenciamento de estado
├── Data/           # Banco de perguntas
└── wwwroot/        # Recursos estáticos
```

## 🚢 Deploy

O deploy é feito automaticamente no GitHub Pages ao fazer push para `main`:
- Seu jogo: `https://{usuario}.github.io/{nome-repo}`

## 📝 Licença

MIT — use para o seu próximo evento!
