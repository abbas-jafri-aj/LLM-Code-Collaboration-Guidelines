# LLM Code Collaboration Guidelines

Opinionated guidelines for collaborating with LLMs on software development.

## What This Is

A set of instructions you paste into your LLM's custom instructions or system prompt. It shapes how the LLM behaves when helping you write code.

## Philosophy

These guidelines prioritize:
- **Thinking before coding** — discuss approaches before generating code
- **Simplicity** — avoid clever solutions and over-engineering
- **Collaboration** — the LLM asks before acting, offers alternatives, and waits for approval

## How to Use

Copy the contents of `guidelines.md` into:
- **Claude**: Project Instructions (in a Project) or Custom Instructions (in Settings)
- **ChatGPT**: Custom Instructions or GPT system prompt
- **Gemini**: Custom Instructions
- **Other LLMs**: System prompt or equivalent

Customize as needed. These are starting points, not rules.

## Opinionated by Design

This is how I like to work with LLMs. You may disagree with some choices. Fork it, modify it, make it yours.

Some opinions expressed:
- Imperative over OOP (usually)
- Over-comment rather than under-comment
- Exit loudly on errors rather than catch silently
- YAGNI over speculative architecture

If these don't fit your style, change them.

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — Use it, modify it, share it. Attribution appreciated.
