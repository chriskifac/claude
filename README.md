# claude

A sandbox for running and testing things built or updated with Claude.

Each experiment lives in its own folder so it can be run, changed or thrown away without affecting anything else.

## Layout

```
claude/
├── README.md        This file
└── <project>/       One folder per experiment, script or tool
    └── README.md    What it is, how to run it, current status
```

## Adding something new

1. Create a folder with a short, descriptive name (for example `invoice-parser`).
2. Add a `README.md` inside it covering:
   - **What** it does
   - **How to run** it (setup steps and the command)
   - **Status**: working, in progress, or abandoned
3. Commit with a message saying what was built or changed.

## Conventions

- Keep secrets out of the repo. Put API keys and passwords in a local `.env` file, which is git-ignored.
- Prefer small, self-contained experiments over one large project.
- When Claude updates something, say what changed and why in the commit message.
