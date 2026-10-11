# claude-skills

A plugin marketplace for Claude. Each plugin groups related skills; skills are plain directories under `plugins/<plugin>/skills/<skill>/`.

## Install

In Claude Code:

```
/plugin marketplace add Fassty/claude-skills
/plugin install product-craft@claude-skills
```

In claude.ai or Cowork: Customize → Plugins → add this repo as a marketplace, then install the plugin.

Update later with `/plugin marketplace update claude-skills`.

## Plugins

| Plugin | Skills | What it does |
|---|---|---|
| `product-craft` | `product-discovery` | Deciding what to build. `product-discovery` runs evidence-driven discovery with a founder, from a raw idea to a build/pivot/stop decision and an MVP learning plan. |

## Adding a skill

1. Create `plugins/<plugin>/skills/<skill-name>/SKILL.md` (directory name = frontmatter `name`).
2. Bump `version` in `plugins/<plugin>/.claude-plugin/plugin.json` and in the plugin's entry in `.claude-plugin/marketplace.json`.
3. `claude plugin validate .` then commit and push.
