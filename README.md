# Order Chat Fix Plugin

Generic, shareable plugin artifact package for Minecraft servers.

## What This Repository Contains
- jar/OrderChatFix-1.0.0.jar
- metadata/plugin.yml
- Documentation files for safe usage and publishing.

## Platform
- Paper/Spigot

## Purpose
Formatting/order fixes for chat output.

## Installation
1. Stop your server (or proxy for Velocity plugins).
2. Copy jar/OrderChatFix-1.0.0.jar into the correct plugins/ directory.
3. Start the server.
4. Configure generated files under your server's plugin config folder.

## Technical Metadata
- Internal plugin name: $(@{Kind=paper; Name=OrderChatFix; Version=1.0.0; Main=me.pera.orderchatfix.OrderChatFixPlugin; RawMeta=name: OrderChatFix
version: 1.0.0
main: me.pera.orderchatfix.OrderChatFixPlugin
api-version: '1.21'
author: Codex
description: Translates MATERIAL_NAME tokens in chat to Turkish names.
depend: [ProtocolLib]
}.Name)
- Internal version: $(@{Kind=paper; Name=OrderChatFix; Version=1.0.0; Main=me.pera.orderchatfix.OrderChatFixPlugin; RawMeta=name: OrderChatFix
version: 1.0.0
main: me.pera.orderchatfix.OrderChatFixPlugin
api-version: '1.21'
author: Codex
description: Translates MATERIAL_NAME tokens in chat to Turkish names.
depend: [ProtocolLib]
}.Version)
- Main class: $(@{Kind=paper; Name=OrderChatFix; Version=1.0.0; Main=me.pera.orderchatfix.OrderChatFixPlugin; RawMeta=name: OrderChatFix
version: 1.0.0
main: me.pera.orderchatfix.OrderChatFixPlugin
api-version: '1.21'
author: Codex
description: Translates MATERIAL_NAME tokens in chat to Turkish names.
depend: [ProtocolLib]
}.Main)

## Important Notes
- This repository is intentionally infrastructure-free (no Docker, no MariaDB dumps, no production compose files).
- Binary internals are preserved from the live-tested artifact. Rebranding inside bytecode or message localization requires source-code rebuild.
- Public release docs are fully in English.

## License
No license is bundled automatically. Add your preferred license before public release.
