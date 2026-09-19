# Git Fundamentals

Git saves snapshots of your project. GitHub stores those snapshots on the web.

## Everyday commands

```powershell
git add .
git status
git commit -m "Describe your change"
git push
```

| Command | Meaning |
|---|---|
| `git add .` | Stage files (prepare them for the next commit) |
| `git status` | See what is staged vs not staged |
| `git commit -m "..."` | Save the staged snapshot on your computer |
| `git push` | Upload commits to GitHub |

## First-time setup on a PC

```powershell
git config --global user.name "Karthik"
git config --global user.email "thebaycraftsystems@gmail.com"
```

Every new commit uses this name and email.

## New project to GitHub

```powershell
git init
git branch -M main
git add .
git commit -m "First commit"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Why a phone needs an https link

A QR code can store any text. Phone cameras only open **https://** web links. A path like `E:\folder\file.doc` will not open on a phone.
