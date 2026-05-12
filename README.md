# Order Chat Fix Plugin

Order Chat Fix is a lightweight chat behavior plugin package.
It is intended for servers that need consistent chat formatting/order behavior adjustments without adding heavy moderation logic.

## What It Does
- Adjusts chat ordering/format handling (implementation-specific)
- Ships with config and locale artifact files
- Designed to run as a minimal runtime utility

## Package Contents
- `jar/OrderChatFix-1.0.0.jar`
- `README.md`
- `SECURITY.md`
- `SANITIZATION_NOTES.md`
- `DISCLAIMER.md`
- `metadata/NOTES.md`

## Platform
- Paper/Spigot

## Installation
1. Stop the server.
2. Copy `jar/OrderChatFix-1.0.0.jar` into `plugins/`.
3. Start server once and let plugin files generate.
4. Review generated `config.yml` and locale resources for your target language.
5. Restart after edits.

## Commands and Permissions
No public command or permission node is declared in plugin metadata.
This plugin is intended to run passively after load.

## When to Use It
- You have chat ordering issues between multiple chat-related plugins.
- You want a small utility layer rather than a full chat suite.
- You need a deployable artifact with minimal operational complexity.

## Troubleshooting
- **No visible effect:** verify plugin startup and check if another chat plugin overrides event priority.
- **Formatting still inconsistent:** place this plugin with compatible chat stack and retest.
- **Unexpected language output:** review locale files in generated plugin directory.

## Notes
- Runtime artifact is included as-is for reproducible deployment.
- Infrastructure files and private config values are intentionally excluded.
