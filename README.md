# clever

Core AI response guidelines, packaged as a Hermes skill.

Seven principles: think before answering, simplicity first, stay within scope,
goal-driven execution, handle uncertainty explicitly, preserve user intent, and
a response quality check before finalizing.

## Install

Clone and copy the skill into your Hermes skills directory:

```bash
git clone https://github.com/Geronimolt/Clever.git
cp -r Clever/skills/clever ~/.hermes/skills/
```

Hermes loads it automatically (the `disable-model-invocation` flag means it is
auto-loaded via config rather than chosen per-task).

## Layout

```
skills/clever/SKILL.md
```