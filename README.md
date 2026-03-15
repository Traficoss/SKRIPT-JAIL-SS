# 🔒 Jail ScreenShare 

Sistema de **Jail e ScreenShare** feito para servidores Minecraft.

Este script permite que staff coloque jogadores em **ScreenShare (SS)** para verificação, com suporte a **silent jail**, bloqueio de comandos e detecção de logout.

# O CODIGO ESTA EM SKRIPT (CODIGO NAO COMPLETO PARA PORTFÓLIO) PARA VER O PROJETO, ATUAL ESTA EM .JAR

---

# ✨ Features

- 🔒 Sistema de **Jail**
- 🤫 **Silent Jail**
- 📍 Sistema de **Set Jail**
- 🚫 Bloqueio de comandos enquanto preso
- 🛑 Bloqueio de movimento
- 💬 Chat local dentro da jail
- ⚠️ Detecta logout durante ScreenShare
- 🔓 Sistema de **Unjail**

---

# 📜 Comandos

| Comando | Descrição |
|-------|--------|
| `/setjail` | Define a localização da jail |
| `/jail <player>` | Coloca o jogador em ScreenShare |
| `/silentjail <player>` | Coloca em SS sem avisar o servidor |
| `/unjail <player>` | Remove o jogador da jail |

---

# ⚙️ Como configurar

Antes de usar o sistema você precisa **definir a jail**.

1️⃣ Vá até o local onde quer que fique a jail.

2️⃣ Use o comando:

```
/setjail
```

Isso irá salvar a localização da jail.

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
