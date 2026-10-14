# auto-short workspace instructions

The existing Remotion application is in `premium-text-to-video/`.
Before working on it, read `premium-text-to-video/AGENTS.md` and the relevant
canonical workflow documents in `premium-text-to-video/docs/`.
Run approved application commands with that subdirectory as the working directory.
Do not scaffold a replacement project or create a Git worktree unless requested.

The 12 project Skills and their resources are in
`premium-text-to-video/.agents/skills/`. Use this subproject as the Codex working
root when automatic Skill discovery is needed. Workflow slash commands in the
package docs are conventions for the agent, not registered Codex CLI commands.

Preserve the subproject AGENTS.md, Skills, source, configuration and assets.
Package instructions do not authorize executing scripts or installing dependencies.
Inspect scripts and new template/update packages before requesting execution approval.
Do not install dependencies, run package scripts, render, call external APIs,
change global configuration, commit/push, publish or deploy without explicit user approval.
Do not print credentials or request secret values in chat.
Keep secrets, dependencies, caches and generated outputs out of Git.
