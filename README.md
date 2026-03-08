# 🔒 Jail ScreenShare Skript

![Minecraft](https://img.shields.io/badge/Minecraft-1.8%2B-green)
![Skript](https://img.shields.io/badge/Skript-supported-blue)
![Status](https://img.shields.io/badge/status-active-success)

Sistema de **Jail e ScreenShare** feito em **Skript** para servidores Minecraft.

Este script permite que staff coloque jogadores em **ScreenShare (SS)** para verificação, com suporte a **silent jail**, bloqueio de comandos e detecção de logout.

---

# ✨ Features

- 🔒 Sistema de **Jail**
- 🤫 **Silent Jail** (sem aviso global)
- 🚫 Bloqueio de comandos enquanto preso
- 🛑 Bloqueio de movimento
- 💬 Chat local dentro da jail
- ⚠️ Detecta logout durante ScreenShare
- 🔓 Sistema de **Unjail automático**

---

# 📜 Comandos

| Comando | Descrição |
|-------|--------|
| `/jail <player>` | Coloca o jogador em ScreenShare |
| `/silentjail <player>` | Coloca em SS sem avisar o servidor |
| `/unjail <player>` | Remove o jogador da jail |

---

# ⚙️ Requisitos

Para usar este script você precisa de:

- **Minecraft 1.8+**
- **Spigot / Paper**
- **Skript Plugin**

Plugins recomendados:

- SkBee (opcional)
- SkQuery (opcional)

---

# 📂 Instalação

1️⃣ Baixe o arquivo `jail.sk`

2️⃣ Coloque na pasta:

```
plugins/Skript/scripts/
```

3️⃣ Execute no servidor:

```
/sk reload jail
```

ou reinicie o servidor.

---

# 📁 Estrutura do projeto

```
jail-skript
│
├── scripts
│   └── jail.sk
│
├── README.md
├── .gitignore
└── .vscode
```

---

# 🛡️ Sistema de ScreenShare

Quando um jogador é colocado em SS:

- ele é **teleportado para a jail**
- **não pode usar comandos**
- **não pode andar**
- chat fica **limitado**

Se ele **sair do servidor durante SS**, o script detecta automaticamente.

---

# 📌 Uso recomendado

Este script é ideal para servidores:

- PvP
- Practice
- KitPvP
- Hardcore

---

# 💡 Melhorias futuras

Algumas ideias que podem ser adicionadas:

- ⏱ Timer de ScreenShare
- 🚫 Ban automático ao deslogar
- 📜 Logs para staff
- 🌐 Integração com Discord webhook
- 📋 Lista de jogadores em SS

---

# 👨‍💻 Autor

Script criado para gerenciamento de **ScreenShare e Jail em servidores Minecraft**.

Caso queira contribuir, abra um **Pull Request** ou **Issue** no repositório.

---

⭐ Se você gostou do projeto, deixe uma **Star no repositório**!
