# OpenWork Skills

Personal skills repository for reusable agent workflows.

## Structure

```text
openwork-skills/
├── README.md
└── skills/
    ├── agent-browser/
    ├── browser-use/
    ├── caveman/
    ├── excalidraw-diagram/
    ├── find-skills/
    ├── frontend-design/
    ├── graphify/
    ├── karpathy-guidelines/
    ├── valyu-best-practices/
    └── vercel-react-best-practices/
```

## Source

These skills were copied from:

```text
C:\Users\me\.agents\skills
```

## Updating

From this repository root:

```powershell
Remove-Item -Recurse -Force .\skills\*
Copy-Item -Path C:\Users\me\.agents\skills\* -Destination .\skills -Recurse -Force
git status
```

## Publishing

Create a GitHub repository named `openwork-skills`, then run:

```powershell
git remote add origin https://github.com/<username>/openwork-skills.git
git push -u origin main
```
