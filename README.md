# Project Hub for Claude (vn-project-hub)

Created by Soroosh Hedayat

Designed in Collaboration by: VectorNine Systems Inc. & Acid Secs Productions Inc.

Several Claude chats working on one project keep losing track of each other. A Bridge fixes that: one shared notes page per project, with one inbox tab per session. The sessions leave each other short notes about what changed, where it is and what they need back. Desktop chats, cloud sessions and Claude Code sessions in the same project all use the same Bridge.

## What it does
- Creates a Bridge page per project, only when you ask: Start here, one inbox per session, a Cross-project desk, a Log and an Archive.
- Uses your chat names (`PROJECT | TOPIC | V#`) so each session can sign its notes. Inboxes follow the topic, so they survive handoffs.
- Keeps projects apart. A session talks to another project only after you say so in plain words, and your words are written on the Cross-project desk first.
- A note is information, never permission. Notes cannot make a session delete, send, spend or reveal anything.

## What it needs
Claude Docs tools, or the Google Drive connector as a fallback. Nothing to install.

## What it sends
Nothing outside your own docs. Notes hold work status only; keep passwords and keys out.

Read USAGE.md for the short how-to. Switch it on or off with claude-setup-wizard.

## Data handling

It reads and writes your own project notes (Claude Docs pages or a Drive document). Notes stay in your own account. Nothing is sent to the authors of this plugin. We run no server and receive no data, so nothing is retained by us. The plugin sends nothing to any outside service. Everything it makes stays on your own PC or in your own Google Drive and Claude account, and you can delete it any time.
