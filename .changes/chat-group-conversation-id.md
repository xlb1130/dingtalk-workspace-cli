---
category: Changed
---

- **Chat group conversation flag** — unifies `dws chat group bots` and `dws chat group members add-bot` on the canonical `--conversation-id` flag, so help, Schema, and Agent recommendations use the same conversation entry point as the rest of the chat command family.
- **Legacy chat flag compatibility** — keeps the previous `--group` (bots) and `--id` (add-bot) flags working as hidden compatibility aliases of `--conversation-id`, including group-name resolution on `chat group bots`, while hiding them from help, Schema, and error hints.
