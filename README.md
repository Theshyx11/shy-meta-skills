# Shy Meta Skills

Codex plugin bundling three meta-thinking skills:

- `shy-knowledge-topology`: Builds a knowledge topology from a single concept, including parent fields, sibling concepts, blind spots, and a Markdown knowledge tree.
- `shy-theory-grounding`: Grounds a practical problem in historical theory, classical thinkers, disciplines, and search keywords.
- `shy-kill-unknow-unknowns`: Reframes a stuck problem by auditing the problem definition, hidden assumptions, missing variables, and minimum breakout experiments.

## Structure

```text
shy-meta-skills/
├── .codex-plugin/
│   └── plugin.json
└── skills/
    ├── shy-knowledge-topology/
    ├── shy-theory-grounding/
    └── shy-kill-unknow-unknowns/
```

## Usage

Install this plugin in Codex, then call the skills by name in a conversation:

- `shy-knowledge-topology`
- `shy-theory-grounding`
- `shy-kill-unknow-unknowns`

## Notes

This repository packages the skills as a portable Codex plugin. The source skills were originally maintained in the Jarvis project under `skills/meta/`.
