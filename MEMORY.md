# MEMORY.md — novus-aexenti
Durable facts about this repo. Dated; newest first. Updated at session wrap-up.

## 2026-10-28
- **Wiki admin = `executor-core/file-administrator/`** ("NovusÆxenti-Housekeeper"). Extended 2026-10-28: model binding GLM-5.2 on OpenRouter (2026-09-06) changed to Gemini by operator order (old value kept under `previous_binding` in `manifest.json`); attached-tool table with real paths; staging flow into `01-inbox/`; Claude Code agent definition `wiki-admin.claude-agent.md`. Tools and skills live in NovAExopia (`tools/wiki-admin/`, `skills/wiki-admin-core/`).
- Repo role (operator): agent configurations, agent logic, configs and pre-compiled agent packages live here.

## 2026-10-05
- Created at wrap-up. AGENTS.md is the only instruction file (the old CLAUDE.md content moved there; Claude Code reads AGENTS.md natively).
- `.github/workflows/notify-vault.yml` pings `c10vis-poem/NovAExorpus` when AGENTS.md or RESUME.md change on main, so the vault rebuilds MASTER-AGENTS.md / MASTER-RESUME.md (secret `VAULT_DISPATCH_TOKEN`).
- Runtime memory stack is canonical in aesop-xi (`AGENTS.md` §Runtime memory stack); this repo references it.
