# 🎙️ ManagerVoiceChat

**ManagerVoiceChat** is a lightweight plugin to **manage voice chat permissions** on your server.  
It works with **Simple Voice Chat** and **Plasmo Voice**, allowing you to **mute/unmute speaking** and **mute/unmute listening** for individual players or the entire server.

✨ Designed for **Paper**, **Spigot**, **Purpur**, **Folia**, and other Bukkit-based servers from **Minecraft 1.13 up to 1.21+**.

---

## ⚡ Features

- 🔄 Works with **Simple Voice Chat** and **Plasmo Voice** simultaneously  
- 🎤 Commands to **mute/unmute speaking** and **mute/unmute listening**  
- 🔑 Full integration with **LuckPerms** for dynamic permissions  
- 📑 **Multi-language support** (`es.yml`, `en.yml`, `de.yml`, …)  
- ⚡ Automatic tab-completion (`players`, `all`, `*`)  
- 🛠️ Runs on **Paper / Spigot / Purpur / Folia**  
- 🕹️ Supports **Minecraft 1.13 – 1.21+**  

---

## 📥 Installation

1. Download the latest release of **ManagerVoiceChat**  
2. Drop the `.jar` file into your server’s `plugins` folder  
3. Make sure you have **LuckPerms** installed and at least one voice chat plugin (**Simple Voice Chat** or **Plasmo Voice**)  
4. Restart your server  

---

## ⚙️ Commands

| Command | Alias | Description | Permission |
|---------|-------|-------------|-------------|
| `/managervoice` | `/mvc` | Shows plugin info | `managervoicechat` |
| `/mvc reload` | — | Reloads configuration and languages | `managervoicechat.command.reload` |
| `/mvc lang global <lang>` | — | Change global language | `managervoicechat.lang.global` |
| `/mvc lang player <lang>` | — | Change your personal language | `managervoicechat.lang.player` |
| `/mvc lang player <player> <lang>` | — | Change another player’s language | `managervoicechat.lang.player.others` |
| `/mvc lang list` | — | List available languages | `managervoicechat.lang` |

⚠️ Using `all` or `*` applies the action to **all connected players**.

---

## 🔑 Permissions

| Permission | Default | Description |
|-------------|---------|-------------|
| `managervoicechat` | `op` | Use `/managervoice` |
| `managervoicechat.command.reload` | `op` | Reload config and languages |
| `managervoicechat.lang.global` | `op` | Change global language |
| `managervoicechat.lang.player` | `true` | Change your personal language |
| `managervoicechat.lang.player.others` | `op` | Change another player’s language |
| `managervoicechat.lang` | `true` | View list of available languages |

Manage these using **LuckPerms** or any other permissions plugin.

---

## 🔧 LuckPerms Integration

ManagerVoiceChat is fully compatible with [LuckPerms](https://luckperms.net/).  
You can assign and revoke all of the above permissions dynamically using LuckPerms commands.

### Examples
Give an admin full control over voice chat:
```bash
/lp user <player> permission set voicechat.admin true
```

Grant a player the ability to change their personal language:
```bash
/lp user <player> permission set managervoicechat.lang.player true
```

Revoke global language change permission from non-admins:
```bash
/lp group default permission set managervoicechat.lang.global false
```

---

## 🌍 Multi-language

ManagerVoiceChat includes YAML-based language files:

- 🇪🇸 **Spanish**  
- 🇬🇧 **English**   
- 🇩🇪 **German**   

You can add your own languages by creating new files inside `plugins/ManagerVoiceChat/lang/`.

---

## 🖥️ Compatibility

- **Server types:** Paper, Spigot, Purpur, Folia, Bukkit  
- **Minecraft versions:** 1.13 → 1.21+  

---

## 📎 Links

- 🌐 [GitHub](https://github.com/PandaDevOfficial)  
- 📦 [Modrinth](https://modrinth.com/user/PandaDev0001)  
- 🛒 [BuiltByBit](https://builtbybit.com/members/pandadev001.656718/)  
- 🔗 [SpigotMC](https://www.spigotmc.org/members/pandadevoffi.1551117/)

---

## 🐞 Bug Reports

Found a bug or an issue?  
Please report it in the [Issues section](https://github.com/PandaDevOfficial/ManagerVoiceChat/issues) of this repository.

