# Claude Mastery

**The complete professional guide to Claude — practical techniques, real prompts, and business workflows.**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## Why Claude?

| Capability | Rating | Notes |
|---|---|---|
| Context window | 200K tokens | Entire codebases, books |
| Instruction following | Excellent | Very precise |
| Long-form writing | Excellent | Consistent quality |
| Code generation | Excellent | Strong reasoning |
| Data analysis | Excellent | With uploaded files |

## Repository Structure

```
claude-mastery/
├── 01-getting-started/    Models, interface, Projects setup
├── 02-prompting/          Claude-specific prompting techniques
├── 03-long-context/       Working with 200K token window
├── 04-use-cases/          Data analysis, coding, research, writing
├── 05-claude-api/         Python API integration
├── 06-projects/           Claude Projects for persistent context
├── prompts/               100+ curated Claude prompts
└── cheat-sheets/          Quick reference
```

## Claude's Superpower: Long Context

Claude can read and reason over entire documents, codebases, or datasets.
Upload a 100-page PDF and ask it to extract key insights, risks, and recommendations.

## XML Tags for Structure

Use XML tags to clearly structure complex prompts:
- `<role>` - Define who Claude should be
- `<task>` - Describe what to do
- `<data>` - Provide the input data
- `<output_format>` - Specify the response format

## Python API

Install: `pip install anthropic`

Key methods:
- `client.messages.create()` - Generate a response
- `system` parameter - Set Claude's role and behavior
- `max_tokens` - Control response length
- `model` - Choose Claude version (claude-opus-4-5, etc.)

## Interview Questions

1. How is Claude different from ChatGPT?
2. What is Constitutional AI?
3. How do you use Claude's long context window effectively?
4. When would you choose Claude over other models?
5. How do XML tags improve Claude prompts?

---

Part of the [Real-World AI Skills Ecosystem](https://github.com/saitejabandaru-in)
