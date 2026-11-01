# anthropics-skills-zcode

A ZCode plugin marketplace containing skills ported from [anthropics/skills](https://github.com/anthropics/skills) so they can be installed in the ZCode desktop app.

## Plugins

| Plugin | Version | Description |
|---|---|---|
| `frontend-design` | 0.1.0 | Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one |

## Install in ZCode

1. Clone this repository (or download it) to any local folder.
2. In ZCode, open **Plugin Marketplace → Add → Add Plugin Marketplace**.
3. Paste the path of the **cloned folder** (the one containing `marketplace.json`), then click **Add**.
4. Open **Personal**, find **Frontend Design** in this market, and click **Install**.
5. In a new task, pick the skill from the composer picker and try it, e.g.:
   *"Design a landing page for a specialty coffee shop in Hanoi"*
   Expected: a design direction with a distinctive palette and typography specific to the brief, not a templated look.

## License & attribution

- The `frontend-design` skill content is © Anthropic PBC, licensed under the **Apache License 2.0** — see [`frontend-design/skills/frontend-design/LICENSE.txt`](frontend-design/skills/frontend-design/LICENSE.txt).
- This repository only repackages the skill for ZCode's plugin format; no other changes are made to the skill content.
