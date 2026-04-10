# person-profiler

**7-axis web research engine: extract core DNA traits, strengths, weaknesses, and a 30-second elevator pitch.**

## Prerequisites

- **Claude Cowork or Claude Code** environment
- **Web search access** — required for real-time person research

## Goal

person-profiler transforms scattered public information into actionable insight. It structures web signals into 7 strategic axes (Career DNA, Decision Patterns, Vision, Reputation, Personality, Network, Current Context), extracts 5-7 core DNA traits, assesses strengths/weaknesses, and generates a 30-second elevator pitch.

## When & How to Use

Deploy when researching someone for meetings, partnerships, hiring, or investment decisions. Runs targeted web research and consolidates into 7-axis framework. For deeper analysis, pair with research-frame.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| Pre-meeting research | `"Profile Jessica Chen, Partner at Sequoia"` | Career DNA→Decision Patterns→Network→30-second pitch for conversation prep |
| CEO leadership analysis | `"Build profile of new CEO of partner company"` | Vision→Reputation→Personality→strengths + blind spots |
| Hiring assessment | `"Profile finalist for Head of Product"` | Career DNA→Decision Patterns→Vision→holistic strengths/weaknesses profile |

## Key Features

- 7-axis research framework: Career DNA, Decision Patterns, Vision, Reputation, Personality, Network, Current Context
- 5-7 core DNA traits synthesis
- Strengths and weaknesses assessment
- 30-second elevator pitch auto-generation
- Web research integration: LinkedIn, press, interviews, public filings

## Works With

- **[research-frame](https://github.com/jasonnamii/research-frame)** — scales to deeper hypothesis-driven analysis
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — informs strategic decisions about partners, investments, hires

## Installation

```bash
git clone https://github.com/jasonnamii/person-profiler.git ~/.claude/skills/person-profiler
```

## Update

```bash
cd ~/.claude/skills/person-profiler && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
