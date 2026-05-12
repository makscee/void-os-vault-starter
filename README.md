# void-os-vault-starter

Starter vault template referenced by the void-os daemon's install script. Provides a minimal Obsidian-openable layout (CLAUDE.md, `skills/`, `agents/`) that the daemon clones into a fresh user's workspace on first run.

Detailed contents — agent prompts, skill scaffolding, install hooks — land in Phase 1 (tasks VOS-72 and beyond). The Phase 0 commit is intentionally bare: just this README, an MIT LICENSE, and a `.gitignore` so the repo exists, is publicly cloneable, and can be referenced from the daemon code.

Architecture spec: see `hub/vault/projects/void-os/specs/2026-05-13-void-os-v1-architecture.md` in the operator's hub for the canonical design of void-os v1.
