# ❓ FAQ

## 🔧 The plugin is not working

- Make sure you are using a supported server (Paper/Spigot/Purpur)
- Check the console for errors
- Verify that the plugin is properly installed in `/plugins`

---

## 🎨 Colors are not showing

- Enable color support in config:

```yaml
chat:
  enable-colors: true
Make sure you have permission:
chatcore.chat.color
🔐 Permissions are not working
Install a permission plugin (recommended: LuckPerms)
Reload permissions after changes
Double check permission nodes
💬 Private messages not working
Ensure private messages are enabled:
private-messages:
  enabled: true
Check permissions:
chatcore.msg
🚫 Messages are being blocked
Review your filter settings
Check blocked words list
Verify anti-spam configuration
⚡ Plugin causes lag?
VoxCore is optimized, but:
Avoid excessive logging
Keep configs clean
Check other plugins for conflicts
🔄 How to reload the plugin?

Use:

/chatcore reload


🧩 Compatibility

VoxCore works with:

LuckPerms
PlaceholderAPI
Most modern server cores
