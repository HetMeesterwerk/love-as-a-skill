# Love as a Skill

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Skill](https://img.shields.io/badge/format-SKILL.md-purple.svg)](SKILL.md)
[![Release](https://img.shields.io/github/v/release/HetMeesterwerk/love-as-a-skill)](https://github.com/HetMeesterwerk/love-as-a-skill/releases)

> A portable Agent Skill for practicing love through communication, repair, emotional regulation, boundaries, and compatibility.

Love is often treated as chemistry, instinct, or destiny. This skill treats love as a trainable practice: noticing patterns, regulating emotions, communicating clearly, repairing conflict, respecting boundaries, and choosing better responses.

This repository contains a `SKILL.md` file that can be used with Claude, Codex, and other agent workflows that support portable skill-style instruction files.

## Quick start

Clone the repository:

```bash
git clone https://github.com/HetMeesterwerk/love-as-a-skill.git
```

Expected structure:

```text
love-as-a-skill/
  SKILL.md
  examples/
```

Use the folder as a portable Agent Skill in any workflow that supports `SKILL.md`-style instruction files.

## What this skill helps with

- Turning relationship problems into concrete skill loops
- Separating facts, feelings, interpretations, and patterns
- Improving difficult conversations
- Repairing conflict after arguments
- Handling jealousy without surveillance or control
- Clarifying compatibility, boundaries, and recurring emotional patterns

## Core model

The skill uses a five-layer analysis structure:

```text
Facts → Feelings → Meaning → Pattern → Skill
```

Instead of asking “Who is right?”, the skill asks:

```text
What is happening?
What am I feeling?
What meaning am I giving this?
What pattern is repeating?
What skill would improve this?
```

## Included examples

The `examples/` folder contains fully worked use cases:

```text
examples/
  conflict-repair-after-argument.md
  jealousy-without-surveillance.md
  compatibility-or-communication.md
```

These examples show how the skill should behave in realistic relationship-reflection scenarios.

## Why save this repo?

Star this repository if you want a reusable reference for:

- relationship reflection with AI agents
- safer communication and repair workflows
- non-surveillance jealousy handling
- portable `SKILL.md` examples
- agent-skill design patterns beyond coding tasks

## Safety boundaries

This skill is not therapy, diagnosis, crisis support, legal advice, or a replacement for professional help.

It should not be used for:

- spying, surveillance, or checking a partner’s devices
- manipulation or coercion
- diagnosing attachment styles or mental disorders
- staying in unsafe or abusive situations
- crisis situations involving self-harm or violence

If a situation involves threats, violence, coercion, stalking, self-harm, or immediate danger, the assistant should shift away from ordinary relationship reflection and toward appropriate safety-oriented support.

## Design principles

This skill is designed to make an assistant:

- slower to judge
- more precise about facts
- more respectful of emotional reality
- less likely to encourage control, surveillance, or manipulation
- more focused on repair, boundaries, responsibility, and practice

Most AI relationship advice gives answers. This skill gives the agent a repeatable operating procedure.

Love is not just a feeling. This makes it executable as a skill.

## Contributing

Contributions are welcome. Useful contributions include:

- new example scenarios
- clearer safety boundaries
- improved wording in `SKILL.md`
- compatibility notes for Claude, Codex, and other agent systems
- test cases for ambiguous relationship prompts

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

MIT License. See [`LICENSE`](LICENSE).
