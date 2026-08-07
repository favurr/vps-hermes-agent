# Obsidian Vault Map

Last updated: 2026-08-07

## Top-Level Structure

- `/root/Obsidian-Vault/`
  - `MAP.md` — this file
  - `README.md`
  - `Achievements/` — daily achievement logs
  - `Leads/` — lead generation research and outreach kits
  - `Routine/` — daily routine logs
  - `Sources/` — reference materials and niche lists
  - `Suggestions/` — daily surprise/suggestion logs
  - `.obsidian/` — Obsidian config/plugins

## Achievements

- Purpose: Daily achievement logs synced from TickTick via cron
- Format: `YYYY-MM-DD.md`
- Examples:
  - `2026-08-01.md`

## Leads

- Purpose: Research and outreach materials for potential clients
- Subdirectories:
  - `Daily/` — daily lead files and outreach kits
    - Format: `YYYY-MM-DD - City.md` for raw lead tables
    - Format: `Business Name Outreach Kit.md` for prepared outreach materials
    - Examples:
      - `2026-08-07 - US Cities Day 1.md` — master lead table for Detroit, Pittsburgh, Cleveland
      - `Cheesy Dave's Outreach Kit.md`
      - `Detroit Outreach Kit.md`
      - `Good Stock PGH Outreach Kit.md`
      - `Hibachi Lou Outreach Kit.md`
      - `Mr. Nick's Fried Chicken Sandwich Outreach Kit.md`
      - `Sahar's Food Lab Outreach Kit.md`
      - `The Better Bean Outreach Kit.md`
      - `The Boonseek Outreach Kit.md`
      - `The Fed Up Momma Farmstand Outreach Kit.md`
  - `Templates/` — reusable outreach templates
    - `Outreach-Style.md`

## Routine

- Purpose: Daily routine execution logs
- Format: `YYYY-MM-DD.md`
- Synced from 🗓️Daily Routine TickTick project via cron at 04:54 WAT
- Examples:
  - `2026-08-01.md` through `2026-08-07.md`

## Sources

- Purpose: Reference materials, niche lists, and research sources
- Examples:
  - `Niches.md`

## Suggestions

- Purpose: Daily surprise/suggestion logs
- Format: `YYYY-MM-DD.md`
- Synced from 💡Daily Suggestion TickTick project via cron at 05:30 WAT
- Examples:
  - `2026-08-01.md` through `2026-08-07.md`

## GitHub Sync

- Remote: `https://github.com/favurr/vps-hermes-agent.git`
- Branch: `main`
- Always pull before editing to avoid merge conflicts
- Always push after editing
- Pull → edit → add → commit → push

## Maintenance Rules

1. Always push to GitHub after editing
2. Update this map when adding/removing files or folders
3. Keep file names consistent with formats above
4. Archive old leads instead of deleting if they might be useful later
5. Use Outreach Kit template for all prepared leads
