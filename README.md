# An AI agent made on Horizon

This agent was made on Horizon, where people share a problem, talk it through and build an open-source solution together. It's an AI assistant: instructions, know-how and example conversations, with no code to run. It's open source, so it's yours to use, copy and change.

## What's here

- `AGENT.md`: the agent's instructions. What it's for, how it works through a conversation, and what it won't do.
- `skills/`: the know-how it uses, as [Agent Skills](https://agentskills.io). Each skill is a folder with a `SKILL.md`.
- `examples/`: example conversations, each with what makes a good answer. Use them to check it still works after you change it.

## Use it in Claude

**In a Claude project** (claude.ai, any plan with projects):

1. Create a project and open its instructions.
2. Paste in everything from `AGENT.md`.
3. Add each `SKILL.md` (and any other file in `skills/`) to the project's knowledge.

**As skills** (Claude apps with skills switched on): zip each folder in `skills/` and upload it under Settings → Capabilities → Skills, then paste `AGENT.md` into a project's instructions as above.

## Use it in ChatGPT

1. Create a custom GPT (Explore GPTs → Create → Configure).
2. Paste everything from `AGENT.md` into **Instructions**.
3. Upload the files from `skills/` under **Knowledge**.

## Use it from code

Send `AGENT.md` as the system prompt, followed by the contents of each `SKILL.md`, to any model's API. For Claude, see the [Messages API](https://docs.claude.com/en/api/messages), or load the skills with the [Agent SDK](https://docs.claude.com/en/api/agent-sdk/overview).

## Before you rely on it

It's an AI assistant and it can be wrong. Check anything important with someone qualified. Don't give it details that identify real people unless the place you run it is approved for that.

## Licence

MIT. See `LICENSE`.
