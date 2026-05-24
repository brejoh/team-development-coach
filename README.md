# Team Development Coach

A folder-based AI coach for new supervisors building a team after an organisational restructure. Built using interpretable context methodology. Each file does one job, and together they turn Claude into a coach.

## What this coach does

This coach will give you the space to think through your topic. It will ask you questions, push back, and provoke. The coach will help you narrow a broad problem down to something you can actually act on today.

It is not designed to be a knowledge base, a mentor, or a teacher.

## Who this coach is for

New supervisors who have inherited or are building a team following an organisational restructure. The coach is designed for the messy reality of that situation. People who may not have chosen to be on the team, trust that hasn't been built yet, and a supervisor figuring out their authority with a new group of people.

## How to use it

### Option 1 — Claude.ai Projects *(simple, manual session tracking)*

1. Go to [claude.ai](https://claude.ai) and create a new Project
2. Upload all the files in this folder to the project knowledge
3. Start a conversation (Claude will read the files and become the coach)

**Session continuity:** At the end of a session, ask Claude to summarise where you got to. Copy the summary into `session.md` and re-upload it. At the start of your next session Claude will pick up where you left off.

**Actions:** Ask Claude to update `actions.md` with any action you agreed. Copy the updated table and re-upload the file.

### Option 2 — Claude Code *(more powerful, automatic session tracking)*

1. Clone this repo locally
2. Open the folder in VS Code with the Claude Code extension
3. Start a conversation — Claude reads the files and becomes the coach

**Session continuity:** Claude will automatically update `session.md` at the end of each session and resume from the right point next time.

**Actions:** Claude will automatically append agreed actions to `actions.md`, building a permanent record over time.

## Folder structure

```
team-development-coach/
├── CLAUDE.md          — routing and session instructions for Claude
├── identity.md        — who the coach is
├── rules.md           — how the coach behaves
├── examples.md        — what good coaching looks like
├── session.md         — state from the last session
├── actions.md         — running log of agreed actions
├── README.md          — this file
└── reference/         — frameworks and domain material
```