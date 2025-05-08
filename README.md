# Memory Bank Cursor

This project is an adaptation of the [Cline Memory Bank](https://docs.cline.bot/improving-your-prompting-skills/cline-memory-bank), tailored for use within Cursor. It manages how Cursor remembers context and information across interactions.

## Overview

The core logic and configurations for the memory bank are located in the `.cursor/rules/` directory. This directory is structured to separate rules for general, always-on memory behavior from rules specific to when an AI agent is active.

- **`.cursor/rules/always/memory-bank/`**: Contains core rules that are always active.
- **`.cursor/rules/agent/memory-bank/`**: Holds rules that apply specifically when an agent is in use, governing aspects like initialization, progress tracking, and updates to the agent's memory.

This setup allows for a flexible and context-aware memory system within Cursor, building upon the concepts of the Cline Memory Bank.

## Quick Start

TODO: Add instructions on how to get started with this project, including any setup, installation, or basic usage commands.
