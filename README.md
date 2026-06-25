# Shy Meta Skills

Codex plugin bundling meta-thinking and mathematical modeling skills:

- `shy-knowledge-topology`: Builds a knowledge topology from a single concept, including parent fields, sibling concepts, blind spots, and a Markdown knowledge tree.
- `shy-theory-grounding`: Searches for historical theory, thinkers, disciplines, papers, and theory traditions behind a concrete practical problem.
- `shy-kill-unknow-unknowns`: Reframes a stuck problem by auditing the problem definition, hidden assumptions, missing variables, and minimum breakout experiments.
- `math-modeling-decomposer`: Turns real-world problems into mathematical objects, variables, formulas, calculations, and validation boundaries.

## Structure

```text
shy-meta-skills/
├── .codex-plugin/
│   └── plugin.json
└── skills/
    ├── shy-knowledge-topology/
    ├── shy-theory-grounding/
    ├── shy-kill-unknow-unknowns/
    └── math-modeling-decomposer/
```

## Usage

Install this plugin in Codex, then call the skills by name in a conversation:

- `shy-knowledge-topology`
- `shy-theory-grounding`
- `shy-kill-unknow-unknowns`
- `math-modeling-decomposer`

## Notes

This repository packages the skills as a portable Codex plugin. The source skills were originally maintained in the Jarvis project under `skills/meta/`.
