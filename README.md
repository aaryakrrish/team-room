# team-room

A Claude Code skill that sets up a private team chat with Claude built in. It's like a small Slack, and you don't need Slack or an Enterprise plan, just a Claude account.

Each room is a private page on claude.ai with:

- channels, unread counts and pinned decisions
- emoji reactions and a smiley picker
- file and picture sharing (paperclip, paste or drag)
- profile photos
- who's online and who's typing
- shared notes that Claude reads
- **@claude** in any channel to bring Claude into the conversation

## Install

Run this once in a terminal:

```bash
git clone https://github.com/aaryakrrish/team-room ~/.claude/skills/team-room
```

No git? Download the [zip](https://github.com/aaryakrrish/team-room/archive/refs/heads/main.zip), unzip it, rename the folder to `team-room` and move it into `~/.claude/skills/`.

## Use

Open Claude Code and say:

> make a team chat room

Claude asks for a room name and channels, then gives you a private link. Open the room and click **Share** to invite your team. Everyone needs to be signed in to Claude.

From Claude Code you can also say things like "read #general in my room", "post this to the room as Claude" or "update the room notes".

## Good to know

- An @claude reply runs on the account of the person who asked, after they allow it the first time.
- Pictures, videos, PDFs and text files work, up to 20 MB each.
- Anyone who can post in a room can delete messages, so only invite people you trust.

## Update

```bash
git -C ~/.claude/skills/team-room pull
```
