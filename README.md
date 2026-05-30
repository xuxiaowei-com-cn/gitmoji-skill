# Gitmoji Skill

[English](README.md) | [中文](README-zh.md)

A Git commit message formatting skill based on [gitmoji](https://gitmoji.dev).

## Overview

This skill helps standardize Git commit messages by using gitmoji shortcodes as commit title prefixes, making commit
history more semantic and visual.

## Usage

When committing, choose the appropriate shortcode from the Shortcode column in [gitmoji.md](gitmoji.md):

```
:shortcode: commit message
```

Format rules:

- No leading space before the shortcode at the start of a line
- A single space is required after the shortcode, followed by the commit message

## Examples

```bash
git commit -m ":memo: add README"
git commit -m ":bug: fix login error"
git commit -m ":sparkles: add user avatar feature"
```

## Files

| File                     | Description                                          |
|--------------------------|------------------------------------------------------|
| [gitmoji.md](gitmoji.md) | Gitmoji reference (Emoji / Shortcode / English / 中文) |
| [CLAUDE.md](CLAUDE.md)   | Skill definition file                                |
