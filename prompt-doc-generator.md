# Prompt Documentation Generator

## Purpose

Creates prompt documentation inside this repository. Ensures all prompt documentations follow [README.md](README.md) guidelines. Designed for use with AI coding assistants to quickly generate well-structured prompt documentation files.

## Usage

Use this prompt when you need to:
- Quickly document a new prompt for the repository
- Ensure consistency across prompt documentation
- Generate a complete `.md` file ready for the prompts repository

Provide the prompt text and any context about its purpose and usage.

## Variables

- `{prompt_text}` - The actual prompt text to document

## Prompt

```
You are creating documentation for this prompt using this guideline: @README.md

{prompt_text}
```
