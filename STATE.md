# STATE.md

Current status of this workspace. Overwrite at the end of each session.

## Status

- **Phase:** initialized (private bridge repo created)
- **Last updated:** 2026-11-14
- **Last touched by:** Muse (Meta Muse, GitHub MCP)

## In progress

- Connecting each AI platform to `LokiTheCoyote/Bridge-Bot`.
- Security checklist review (2026-11-14): repo private and secret-free verified; 2FA, password manager, and OAuth grants review still open — owner-only.

## Next steps

1. Owner confirms the three open security items: 2FA on each bridged account, password manager in use, OAuth grants reviewed (Settings → Applications → Authorized OAuth Apps).
2. Connect GitHub on the remaining platforms (Grok, Gemini AI Studio, Claude, GitHub Copilot).
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
| Claude | pending | GitHub connector / MCP server |
| Copilot | pending | built-in GitHub access |
| Muse | connected | GitHub MCP (OAuth + Muse GitHub App); read of all repo files verified 2026-11-14 |

## Security checklist — reviewed 2026-11-14

- [x] Repo is private (verified via API)
- [x] No secrets, tokens, passwords, or personal data in any repo file (all files read 2026-11-14)
- [x] Quarterly token rotation reminder logged (next review 2027-02-13)
- [ ] 2FA enabled on every bridged account — owner to confirm
- [ ] Password manager in use (1Password or Bitwarden) — owner to confirm; 1Password not connected to Muse
- [ ] OAuth grants reviewed after setup — owner to review at Settings → Applications → Authorized OAuth Apps
