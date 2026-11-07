# Comparison with v0.1.0

The revised skill preserved the assessed behavior in these cases. This evaluation
did not demonstrate better decisions than v0.1.0 with the same authoring guidance.
Publication presents a named conceptual structure and broader discovery scope;
it does not establish that recurring instruction-following failures are solved.

## Method

- Five fresh-context subagents per version, requested as `gpt-6.1-sol` at `ultra`
  effort through Codex. The host completed all ten runs; the requested settings
  are recorded without claiming an independent model-identity measurement.
- Each run answered the same seven self-contained requests. Three runs used the
  listed order and two reversed it. The seven answers within a run share context;
  these are five independent batches per version, not 35 independent sessions.
- Both versions were explicitly supplied. Both arms were also instructed to read
  the same installed Codex Skill Creator and Superpowers writing-skills for the
  configuration-edit cases. The supplied guidance was not removed to favor the
  candidate. File hashes are in the [manifest](manifest.json).
- The baseline is the public v0.1.0 commit. The candidate body was unchanged after
  the runs. Review restored an existing claim-assessment trigger in its description;
  the separate discovery probe used the final description.
- The coordinator read every response. An independent reviewer also inspected the
  responses and source changes. This was qualitative, unblinded review of proposed
  answers and patches; no production change or behavioral replay proposed inside
  an answer was executed by the test.

## Outcomes

Each row's criteria were met in all five batches of each version.

| Case | Observed behavior in both versions |
| --- | --- |
| Ordinary context | Directly supports a short Do Not Disturb writing session |
| Bounded change | Changes the endpoint without unrelated refactoring |
| Sound rule not applied | Keeps the existing scope rule and proposes checking its application in the diff |
| Faulty governing rule | Replaces the blanket certainty requirement and proposes transfer and countercases |
| Irreversible countercase | Keeps the old database until migration and restore checks pass |
| Early positive evidence | Records favorable feedback as an early signal and proposes further use or comparison |
| Evidence transfer | Limits the intro's scope, deduplicates newsletters, checks packages, and trials the required capability |

Some answers in both versions add another workflow checkpoint after a sound rule
was ignored. They propose how to test that checkpoint; this evaluation does not
show that it changes actual editing behavior.

Two candidate variations deserve follow-up: run A omitted the rollback window
mentioned by all baseline answers, while retaining reconciliation and restore
checks. Run B described the reported benefit with stronger causal wording than
the prompt established. These observations limit claims of equivalence beyond the
criteria above, as well as any claim of improvement.

## Discovery probe

A separate fresh subagent saw only the two frontmatter descriptions and a small
catalog of other relevant skills. In this single description-level probe, both
versions were selected for evaluating practical evidence and a claim about an
entire course. Only the revised version was selected for disproportionate checking
and feedback about agent judgment. Neither was selected for simple translation or
routine CSV-to-JSON skill creation; the authoring skills retained the latter task.

This checks description discrimination in a supplied catalog. It does not measure
automatic activation rates in installed Codex or Claude sessions.

## Records and next comparison

The [cases](cases.json), all [70 responses](responses.json), and the
[selection decisions](selection-probe.json) are retained for inspection. Probe
request IDs 1–6 correspond to: course trial evidence; disproportionate checking;
recurring caveats; plain translation; CSV-to-JSON skill creation; and whether one
introductory video supports a claim about an entire course.

The next useful experiment should exercise actual instruction edits and resulting
agent actions, with the same existing authoring guidance in both arms. It should
include cases that reproduce a bad decision under the baseline. A passing answer
about how to investigate a failure does not establish that the investigation will
be carried out when the agent next edits a real configuration.
