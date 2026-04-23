# Facebook Post Writer

Master authentic Facebook content generator using emotion-first, phased architecture. Creates posts that sound genuinely human through cognitive state simulation, not just rule-following. Use when the user asks to write a Facebook post, create content for Facebook groups, draft a personal Facebook update, compose a group discussion post, write a Facebook page post, or needs help with Facebook engagement. Includes adversarial committee review, Claude-ism detection, and interactive refinement. Supports personal updates, group posts, page content, long-form posts, photo/video captions, and community discussion starters. Handles the "See More" fold and Facebook's unique relational, warm-toned culture.

## What this repo contains

- `SKILL.md` — the primary agent skill definition and workflow.
- `references/` — supporting playbooks, platform rules, examples, or data used by the skill.

## Reference material

- `references/examples.md`
- `references/post-formats.md`
- `references/tool-mentions.md`
- `references/communities.md`
- `references/claude-isms.md`

## Installation

Copy this repository or the skill directory into your agent's skills directory, then load the skill by name when the task matches its use case.

```bash
# example
cp -R facebook-post-writer ~/.claude/skills/facebook-post-writer
```

## Repository layout

```text
references/
  claude-isms.md
  communities.md
  examples.md
  post-formats.md
  tool-mentions.md
LICENSE
SKILL.md
```

## Notes

The root README summarizes the live repository contents. The complete operational instructions remain in `SKILL.md`.
