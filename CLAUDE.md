# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

KeepCalm is a Zed editor theme extension. It provides a dark, calm color scheme focused on reducing visual noise during software development.

## Project Structure

- `extension.toml` - Extension manifest with package metadata
- `themes/keepcalm.jsonc` - Theme definition file (JSONC format with comments allowed)

## Theme Schema

The theme file follows Zed's theme schema v0.2.0: https://zed.dev/schema/themes/v0.2.0.json

Key sections in the theme JSON:
- `style` - UI colors (background, borders, elements, text)
- `style.syntax` - Syntax highlighting colors
- `style.terminal.ansi.*` - Terminal ANSI colors
- `style.players` - Cursor and selection colors

## Testing the Theme

Copy the extension to Zed's dev extensions folder:
```bash
cp -r . ~/.config/zed/extensions/installed/keepcalm
```

Or use Zed's "Install Dev Extension" command from the command palette.

## Color Palette Reference

- Background: `#1d191a`
- Foreground: `#e7e8ea`
- Accent (keywords, brackets): `#e7809c`
- Functions: `#d4c79a`
- Strings: `#7fac82`
- Types/Tags: `#efac71`
- Comments: `#6e7681`
