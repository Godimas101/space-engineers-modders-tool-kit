# AGENTS.md — space-engineers-modders-tool-kit

Curated download hub for Chris's Space Engineers modding tools. Not itself a tool — a landing page + README pointing at all the individual tool repos (universal-image-converter, universal-audio-converter, claude-usage-monitor, se-claude-skill) with quick-start guides. Distributed as a GitHub Releases page users bookmark.

## What this is

Curated download hub for Chris's Space Engineers modding tools. Not itself a tool — a landing page + README pointing at all the individual tool repos (universal-image-converter, universal-audio-converter, claude-usage-monitor, se-claude-skill) with quick-start guides. Distributed as a GitHub Releases page users bookmark.

## Where work lives (RULE — non-negotiable)

**Every task on this repo is a ticket on the [Personal Projects board](https://github.com/users/Godimas101/projects/2).** YOU (the agent) create the ticket BEFORE touching anything. No exceptions for "small" work.

Concrete rules — same as everywhere:

- **Starting work?** Open a ticket, add to the board, set Status = **In Progress**, then start.
- **Have an idea for later?** Ticket in **Backlog**. Not in memory, not in a README, not in NOTES.md.
- **Need Chris to check something before closing?** Move to **In QA** and comment what he needs to look at. Do NOT set to Done — that's Chris's call after review.
- **Finished + verified yourself?** Close the ticket with a closing summary (what you did / problems + solutions / anything NOT done).
- **Same-session micro-work?** Open + close in the same session — but the ticket exists.
- **Older than 30 days in Done?** The weekly cron moves it to Archived. The closed ticket persists.

Ticket body shape: see memory `[[feedback-ticket-body-shape]]` — What/Why → Acceptance → Related → Notes. Priority defaults to P2, Kind defaults to Feature.

## How to verify (before flagging In QA or closing)

- If adding a new tool to the kit: verify the tool's GitHub Releases page has a downloadable asset before linking.
- Update README table + per-tool section with `vX.Y` version. Version numbers should match the latest release of each tool.
- Any screenshot updates: match the current UI of the actual tool, not a stale version.

## MUST NOT

- Add tools that aren't Chris's or that don't have a clear license — the toolkit's brand is 'trustworthy free tools'.
- Modify or duplicate the individual tools' code here — this repo just references them.

## Related

- Tools it hubs: [`universal-image-converter`](https://github.com/Godimas101/universal-image-converter), [`universal-audio-converter`](https://github.com/Godimas101/universal-audio-converter), [`claude-usage-monitor`](https://github.com/Godimas101/claude-usage-monitor), [`se-claude-skill`](https://github.com/Godimas101/se-claude-skill)

---

*Part of Chris's `Godimas101` personal repos. Companion guide: [`personal-projects/docs/git-infrastructure.md`](https://github.com/Godimas101/personal-projects/blob/main/docs/git-infrastructure.md) covers the full infrastructure.*