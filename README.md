# ⚡ SuperClaude Builder

A advanced command composition interface for **SuperClaude**.

## Overview

SuperClaude Builder is a single-page web application that helps users quickly build and compose SuperClaude commands. Through an intuitive graphical interface, users can select commands, configure flags, specify arguments, and preview the generated command string in real-time.

## Key Features

- **Dual Command Modes**: Support for Slash commands (`/sc:command`) and Agent commands (`@agent`)
- **Smart Flag System**: Dynamically displays relevant flag options based on selected command
- **Bilingual Interface**: Full i18n support with one-click language switching (EN/中文)
- **Command History**: Auto-saves recent 5 commands with quick copy support
- **Keyboard Shortcuts**: Efficient operation experience

## Quick Start

Simply open `superclaude-builder.html` in your browser. No installation or dependencies required.

### Basic Workflow

1. Select command type (Slash or Agent)
2. Choose specific command or Agent
3. Enter task arguments
4. Configure desired flags
5. Copy the generated command

## Keyboard Shortcuts

| Shortcut            | Action                               |
| ------------------- | ------------------------------------ |
| `Ctrl/Cmd + C`      | Copy command (when no text selected) |
| `Ctrl/Cmd + L`      | Toggle language                      |
| Middle Mouse Button | Copy command                         |

## Technical Implementation

- **Pure Frontend**: Single HTML file, zero dependencies
- **Modern CSS**: CSS variables, glassmorphism effects, responsive layout
- **Local Storage**: Command history persistence

## License

MIT
