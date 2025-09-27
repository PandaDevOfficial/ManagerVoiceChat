#  ManagerVoiceChat 🎙️

**ManagerVoiceChat** is a lightweight plugin to **manage voice chat permissions** across multiple platforms.  
It’s designed to run on **Paper**, **Spigot**, **Purpur**, **Folia** and other Bukkit-based servers from **Minecraft 1.13 up to 1.21**.

It works seamlessly with the two most popular Minecraft voice chat plugins:
- [Simple Voice Chat](https://www.curseforge.com/minecraft/bukkit-plugins/simple-voice-chat)
- [Plasmo Voice](https://www.spigotmc.org/resources/plasmo-voice.91064/)

With this plugin you can quickly **mute/unmute speaking** or **mute/unmute listening** for individual players or the entire server, regardless of which voice chat plugin they use.

---

## ✨ Features

- ✅ Compatible with **Simple Voice Chat** and **Plasmo Voice** simultaneously.
- ✅ Commands to **mute/unmute speaking** and **mute/unmute listening**.
- ✅ LuckPerms support for dynamic permission handling.
- ✅ Automatic tab-completion for player names and `all` / `*`.
- ✅ Works on **Paper / Spigot / Purpur / Folia** (Bukkit API).
- ✅ Supports **Minecraft 1.13 – 1.21**.

---

## 📥 Installation

1. Download the latest release of **ManagerVoiceChat**.
2. Drop the `.jar` file into your server’s `plugins` folder.
3. Make sure you have **LuckPerms** installed and at least one voice chat plugin (**Simple Voice Chat** or **Plasmo Voice**, or both).
4. Restart your server.

---

## 🔧 LuckPerms Integration

ManagerVoiceChat is fully compatible with [LuckPerms](https://luckperms.net/).  
You can assign and revoke all of the above permissions dynamically using LuckPerms commands.

### Examples
Give an admin full control over voice chat:
```bash
/lp user <player> permission set voicechat.admin true
```
---
## 📝 Configuration

No initial configuration is required — just install and go.

---

## 🖥️ Compatibility

- **Server types:** Paper, Spigot, Purpur, Folia, other Bukkit-based servers.
- **Minecraft versions:** 1.13 to 1.21+.  
