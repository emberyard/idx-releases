# IDX

[![Latest release](https://img.shields.io/github/v/release/emberyard/idx-releases?label=latest)](../../releases/latest)
&nbsp;macOS, Apple Silicon · free during the preview

**One Mac app that runs the coding agents you already pay for (Claude, Codex, Gemini, Grok, Cursor, Kimi, OpenCode) side by side, on your own accounts.** No IDX server, no telemetry: your chats stay on your Mac.

Screenshots and the full story: **[idx.irahulsoni.com](https://idx.irahulsoni.com)**

This repository only serves the downloads and the update feed the app reads. The app's source is not here.

## Download

Get the `.dmg` from the **[latest release](../../releases/latest)**, open it and drag IDX to Applications.

## Requirements

Apple only for now: IDX runs on Mac (Apple Silicon), with the iPhone app for approvals and replies. It started as the builder's own daily tool, so it was built for the devices he uses. Windows, Linux and Android are planned.

- A Mac with Apple Silicon, macOS 13 Ventura or later.
- At least one agent CLI installed and signed in with your own account (for example `claude` or `codex`). IDX drives these CLIs; usage counts against your own plans, under each vendor's terms.
- Builds are signed with a Developer ID and notarized by Apple.

## Updates

IDX updates itself. When a new version is ready, a **Restart to update** button appears in the app. Nothing restarts until you press it, and your chats and windows come back afterwards. Every version's notes are on the [releases page](../../releases) and in the app under Help, What's New.

To hear about new versions: subscribe to the [releases feed](../../releases.atom), or **Watch → Custom → Releases** on this repository.

## What works today

- **Several accounts per agent, each model once.** Pick the account in one click from the model picker; each shows its own limit.
- **Limits in sight.** Percent left and when it resets, per account, in plain words.
- **Switch agent in the middle of a chat.** The thread is handed over; switching back resumes the first agent's own session.
- **Workers on other agents.** A lead chat hands parts of a task to other CLIs and gets their results back.
- **Parallel tries.** Run one request several ways and keep the one you want.
- **Every past chat, from every CLI.** Sessions saved on this Mac by Claude, Codex, Gemini, Grok, Cursor, Antigravity, Kimi and OpenCode, grouped by folder, one click to resume.
- **Approvals from the iPhone app.** The phone talks to your Mac directly (same network, or a private network such as Tailscale).

## Not great yet

- Apple only for now: Mac (Apple Silicon) and the iPhone app. Windows, Linux and Android are planned; no dates.
- An early preview that changes every week; some screens are still being polished.
- Each agent's own CLI must be installed and signed in.
- A cockpit for agents, not an editor: no language server, no code navigation.
- Continuing at a rate limit works on a limit simulator; it is not yet proven on a real vendor limit.
- Antigravity runs only in its own terminal (Google's terms).

## What's coming

From the open tickets. The list changes weekly and no dates are promised.

- Lock screen alerts on the iPhone.
- Reaching your Mac from the phone away from home Wi‑Fi.
- Continuing on another of your accounts at a real limit.
- Seeing every agent a chat starts, and what each one did.
- Importing memories and instructions from the files you already use (`CLAUDE.md`, `AGENTS.md`, `GEMINI.md`).
- A side chat.
- An optional account and sign in.
- Windows, Linux and Android versions.

## Report a problem

Open an [issue](../../issues) on this repository. Say which version you run (Help, About) and what you expected to happen.

## Privacy

IDX has no server, account or analytics of its own. Each agent CLI talks to its own vendor as it does without IDX. Details: [idx.irahulsoni.com/privacy.html](https://idx.irahulsoni.com/privacy.html).

## Please do not edit the release files

Installed copies of IDX read the files attached to the releases here to find updates.

---

Built by [Rahul Soni](https://irahulsoni.com). IDX is an independent app. Claude, Codex, Gemini, Grok, Cursor, Kimi, OpenCode and Antigravity are trademarks of their owners, and none of them endorses IDX.
