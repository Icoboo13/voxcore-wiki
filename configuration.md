# ⚙️ Configuration

VoxCore is fully configurable via `config.yml`.

## Example

```yaml
chat:
  format: "&7[%rank%] %player%: %message%"
  enable-colors: true

channels:
  global:
    enabled: true
  staff:
    permission: "chatcore.staff"
Tips
Use & for colors
Permissions control access to features
Restart or reload after changes

# 💬 chat-system.md

```md
# 💬 Chat System

## Channels

VoxCore supports multiple chat channels:

- Global
- Staff
- Private


## Formatting

You can fully customize chat format:


&7[%rank%] %player%: %message%


## Permissions

Control access to channels:

- `chatcore.chat.global`
- `chatcore.chat.staff`
