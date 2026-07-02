# Shy Meta Skills

Codex plugin bundling Shy meta-thinking, research decomposition, and quant strategy skills:

- `shy-knowledge-topology`: Builds a knowledge topology from a single concept, including parent fields, sibling concepts, blind spots, and a Markdown knowledge tree.
- `shy-theory-grounding`: Searches for historical theory, thinkers, disciplines, papers, and theory traditions behind a concrete practical problem.
- `shy-kill-unknow-unknowns`: Reframes a stuck problem by auditing the problem definition, hidden assumptions, missing variables, and minimum breakout experiments.
- `shy-sop-path-decomposer`: Decomposes rough SOPs, broad directions, or execution paths into nodes, inputs, outputs, judgment criteria, and fallback branches.
- `math-modeling-decomposer`: Turns real-world problems into mathematical objects, variables, formulas, calculations, and validation boundaries.
- `quant-variable-decomposer`: Audits quant strategy assumptions, variables, labels, out-of-sample validation, execution cost, and kill conditions.
- `james-simons`: Generates James Simons style quant research prompts from the current context.
- `shy-language-precision-auditor`: Audits vague language, missing variable fields, causal gaps, judgment criteria, and problem framing.

## Structure

```text
shy-meta-skills/
├── .codex-plugin/
│   └── plugin.json
└── skills/
    ├── james-simons/
    ├── math-modeling-decomposer/
    ├── quant-variable-decomposer/
    ├── shy-kill-unknow-unknowns/
    ├── shy-knowledge-topology/
    ├── shy-language-precision-auditor/
    ├── shy-sop-path-decomposer/
    ├── shy-theory-grounding/
    └── ...
```

## Usage

Install this plugin in Codex, then call the skills by name in a conversation:

- `shy-knowledge-topology`
- `shy-theory-grounding`
- `shy-kill-unknow-unknowns`
- `shy-sop-path-decomposer`
- `math-modeling-decomposer`
- `quant-variable-decomposer`
- `james-simons`
- `shy-language-precision-auditor`

## Notes

This repository packages the skills as a portable Codex plugin. The source skills are maintained in the Jarvis project under `skills/meta/`.
