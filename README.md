# Skills

Personal skills repository for reusable agent workflows.

## Structure

```text
Skills/
├── README.md
└── skills/
    ├── agent-browser/
    ├── browser-use/
    ├── business-reporting/
    ├── caveman/
    ├── client-communication/
    ├── docx-automation/
    ├── excel-analysis/
    ├── excalidraw-diagram/
    ├── find-skills/
    ├── graphify/
    ├── impeccable/
    ├── karpathy-guidelines/
    ├── meeting-notes/
    ├── pptx-generation/
    ├── requirement-gathering/
    ├── solution-walkthroughs/
    ├── spreadsheet-automation/
    ├── taste-skill/
    ├── technical-documentation/
    ├── valyu-best-practices/
    └── vercel-react-best-practices/
```

## Source

The base skills were copied from:

```text
C:\Users\me\.agents\skills
```

Additional skills:

- `impeccable`: https://github.com/pbakaus/impeccable/releases/tag/skill-v3.1.1
- `taste-skill`: https://github.com/leonxlnx/taste-skill
- Custom workflow skills: `docx-automation`, `pptx-generation`, `excel-analysis`, `spreadsheet-automation`, `technical-documentation`, `business-reporting`, `client-communication`, `requirement-gathering`, `meeting-notes`, and `solution-walkthroughs`

## Updating

From this repository root:

```powershell
Copy-Item -Path C:\Users\me\.agents\skills\* -Destination .\skills -Recurse -Force
git status
```

## Publishing

Create a GitHub repository named `openwork-skills`, then run:

```powershell
git remote add origin https://github.com/<username>/openwork-skills.git
git push -u origin main
```
