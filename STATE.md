# STATE.md

Current status of this workspace. Overwrite at the end of each session.

## Status

- **Phase:** initialized (private bridge repo created)
- **Last updated:** 2026-11-14
- **Last touched by:** Claude (Sonnet 5.5, claude.ai mobile app; no direct GitHub access, drafted via paste)

## In progress

- Connecting each AI platform to `LokiTheCoyote/Bridge-Bot`.
- Claude is working in manual mode (see table): owner pastes files, Claude drafts updates, Bridge Bot commits after owner approval.

## Next steps

1. Connect GitHub on the remaining platforms (Grok, Gemini AI Studio, GitHub Copilot).
2. Complete the security checklist in SECURITY.md.
3. Add your first real task and let an agent pick it up.

## Quarterly rotation reminder

- **Next review:** 2027-02-13 — review and rotate all connected OAuth tokens and API keys.
- Log the result here when done.

## Connected platforms

| Platform | Connected | Notes |
|----------|-----------|-------|
| Bridge Bot (Grok Bot) | connected | GitHub CLI on bot computer |
| Grok | pending | grok.com/connectors → GitHub |
| ChatGPT | connected | Private repository read verified 2026-11-13 via ChatGPT GitHub connector; this status commit tests direct write access. |
| Gemini | pending | AI Studio GitHub sync |
| Claude | manual (paste via Bridge Bot) | Direct GitHub link attempted 2026-11-14 and failed; appears unavailable on the free plan. Claude read AGENTS.md, STATE.md and HANDOFF.md from a pasted attachment (second-AI read check passed). Bridge Bot pushes Claude's drafts after owner says yes. |
| Copilot | pending | built-in GitHub access |
