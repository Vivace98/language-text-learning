# language-text-learning

AI-assisted language learning skills for analyzing natural dialogue, subtitles, and text.

This repository focuses on understanding how language actually works in real usage rather than memorizing isolated grammar rules.

Designed for Codex / Claude-style skill workflows.

---

# Skills

## English / B2

### `English-text-learning`

Analyzes English dialogue and spoken expressions using native-speaker thinking.

Focus areas:

- verbs and phrasal verbs
- collocations
- spoken English patterns
- pragmatic softeners
- native conceptual metaphors
- Chinese learner pitfalls

Goal:

Train natural English intuition and conversational understanding at the B2+ level.

---

## Italian / A2

### `Italian-text-learning`

Analyzes Italian text and extracts important linguistic structures for learners.

Focus areas:

- verb conjugation recognition
- noun gender and plural patterns
- adjective agreement
- grammar structures
- high-frequency vocabulary

All explanations are written in English.

Goal:

Help learners recognize how Italian grammar and sentence structures work in authentic text.

---

# Repository Structure

```text
language-text-learning/
│
├── README.md
│
├── English/
│   └── B2/
│       └── SKILL.md
│
└── Italian/
    └── A2/
        └── SKILL.md
```

---

# Installation / Usage

Place the repository folders inside the `skills/` directory of your Codex or Claude workflow environment.

Example:

```text
codex-project/
│
├── skills/
│   └── language-text-learning/
│       ├── English/
│       └── Italian/
│
└── ...
```

The skills can then be invoked directly by the agent.
