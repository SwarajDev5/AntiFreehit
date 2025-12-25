![AntiFreehit](https://i.postimg.cc/X7FYbnq8/Chat-GPT-Image-Dec-25-2025-02-06-18-PM-(1).png)

**An advanced combat-tag & anti-freehit protection plugin for Minecraft servers.**

AntiFreehit provides a powerful and fair combat system designed to prevent
freehitting, combat abuse, and unfair fight interruption. It is built for
PvP-focused servers where players should commit to fights without exploiting
commands, teleportation, or logout mechanics.

With region-based control, configurable punishments, and a clean ActionBar UI,
AntiFreehit keeps PvP competitive, balanced, and abuse-free at all times.

---

## Features

- **Combat Tag System**
  - Automatically tags players when they engage in combat.
  - Configurable combat tag duration.
  - Prevents third-party fight interference (freehitting).

- **Anti Combat-Logout**
  - Detects players logging out during combat.
  - Optional kill-on-quit punishment.
  - Stops players from escaping fights by disconnecting.

- **Region-Based Control**
  - Enable AntiFreehit only in Non-FFA regions.
  - Fully ignore configured FFA regions.
  - Ideal for AxePvP, NetPot, arenas, and duel servers.

- **ActionBar Combat Timer**
  - Displays remaining combat time in the ActionBar.
  - Customizable format, symbols, colors, and bar count.
  - Clean visual feedback without chat spam.

- **Punishment Systems**
  - Optional kick system for repeated freehit attempts.
  - Optional ban system with custom ban commands.
  - Fully configurable thresholds.

- **Multi-Language Support**
  - Message-based language system.
  - Supports: en, de, fr, it, ru, es.
  - Find on github: [Github](https://github.com/SwarajDev5/AntiFreehit)

---

## Commands

All commands are under the base command `/afh`:

- `/afh` – Main AntiFreehit command  
- `/afh reload` – Reload the configuration and messages  
- `/afh whitelist` – Manage command whitelist  

---

## Permissions

- `antifreehit.*` – Access to all AntiFreehit features  
- `antifreehit.reload` – Reload configuration *(default: OP)*  
- `antifreehit.bypass` – Bypass combat restrictions *(default: OP)*  

---

## Example Configuration

```yaml
# Messages file (Available: en, de, fr, it, ru, es)
messages: "messages_en.yml"

# Non-FFA regions where anti-freehit works
nonffa:
  - "axepvp"
  - "nethpot"

# FFA regions (ignored)
ffa:
  - "ffapvp"
  - "arenapvp"
```
