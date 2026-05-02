# 💬 Chat System

VoxCore provides a powerful and flexible chat system designed for full control over player communication.

---

## 🌐 Channels

The plugin supports multiple chat channels:

| Channel | Description |
|--------|------------|
| Global | Default chat for all players |
| Staff | Private channel for staff members |
| Custom | Create your own channels |

---

## ⚙️ Channel Configuration Example

```yaml
channels:
  global:
    enabled: true
    format: "&7[%rank%] %player%: %message%"
  
  staff:
    enabled: true
    permission: "voxcore.staff"
    format: "&c[STAFF] %player%: %message%"
🎨 Chat Formatting

Customize how messages appear using placeholders:

Placeholder	Description
%player%	Player name
%message%	Message content
%rank%	Player rank
%prefix%	Custom prefix
🔐 Permissions
Permission	Description
voxcore.chat.global	Access global chat
voxcore.chat.staff	Access staff chat
voxcore.chat.color	Use color codes
⚡ Features
Multi-channel support
Custom formats per channel
Permission-based access
Placeholder support
Lightweight and optimized
💡 Tips
Use & for color codes
Combine with permission plugins like LuckPerms
Keep formats simple for readability
