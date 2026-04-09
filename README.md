# AI Git Commit Message Generator

A simple Python tool that generates conventional commit messages from a staged Git diff using a LLM served via API.

It automatically:
- Reads staged changes from ```git add```
- Sends the diff to a LLM using the provided API (local or cloud) for processing
- Generates a commit message following the Conventional Commits specification
- Prints the message in console for viewing
- Copies the message to user clipboard for easy use

---
