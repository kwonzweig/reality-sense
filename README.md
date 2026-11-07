# Practical Judgement

An agent skill for useful decisions in context, distributed as `reality-sense`.

Practical Judgement groups guidance under established concepts:

- **Resource rationality:** spend attention and effort in proportion to their likely benefit, including the costs of delay and complexity.
- **Double-loop learning:** examine the criterion behind a poor decision and distinguish a faulty rule from a sound rule that was not applied.
- **Evidence synthesis:** weigh observations, independent reports, adoption, and demonstrated capabilities against the user's actual needs.

The [skill](skills/reality-sense/SKILL.md) contains the concise rules. Its [source notes](skills/reality-sense/references/concepts.md) explain the concepts and their relationship to existing skills. Repo authors follow [AGENTS.md](AGENTS.md).

If you have permission to use the skill, copy the [skill folder](skills/reality-sense) into your project's `.agents/skills/` for Codex or `.claude/skills/` for Claude Code.

Try asking, “The vendor promises overnight setup, but two teams like ours needed a week. Use reality-sense to help me decide what to check before we book the rollout.”

For feedback about an agent's judgment, try: “Use reality-sense to examine why this small change became a broad refactor. Was the governing rule wrong, or was an existing rule not applied?”

The [comparison with v0.1.0](docs/evaluation/2026-11-07/README.md) records 70 responses and a separate discovery probe. Both versions handled the assessed cases appropriately; improved decision quality over the prior version was not demonstrated.

All rights reserved. See the [license](LICENSE).
