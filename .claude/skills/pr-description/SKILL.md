---
name: pr-description
description: Writes professional pull request descriptions. Use whenever the user asks to create a PR description, summarize code changes, or prepare a pull request.
allowed-tools: Bash, Read
model: sonnet
---

# PR Description Skill

When writing a pull request:

1. Run:

git diff main...HEAD

2. Summarize the changes.

Use this format:

## What

One sentence explaining the purpose.

## Why

Why this change was needed.

## Changes

- List major modifications.
- Mention renamed or deleted files.
- Mention testing performed.
