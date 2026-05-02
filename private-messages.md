# 📩 Private Messages

VoxCore includes a fully featured private messaging system, allowing players to communicate directly.

---

## ✨ Features

- Direct player-to-player messaging
- Quick reply system
- Ignore functionality
- Fully customizable formats
- Permission-based access

---

## 💬 Commands

| Command | Description |
|--------|------------|
| /msg <player> <message> | Send a private message |
| /tell <player> <message> | Alias for /msg |
| /w <player> <message> | Alias for /msg |
| /reply <message> | Reply to last private message |
| /r <message> | Alias for /reply |
| /ignore <player> | Ignore messages from a player |
| /unignore <player> | Stop ignoring a player |

---

## 🔐 Permissions

| Permission | Description |
|------------|------------|
| voxcore.msg | Send private messages |
| voxcore.reply | Use reply command |
| voxcore.ignore | Ignore players |

---

## ⚙️ Configuration Example

```yaml
private-messages:
  enabled: true
  format:
    sender: "&8[&aTo %target%&8] &7%message%"
    receiver: "&8[&aFrom %sender%&8] &7%message%"
💡 Notes
Players can reply instantly using /reply
Ignored players will not be able to send messages to you
All messages can be logged if enabled in config
