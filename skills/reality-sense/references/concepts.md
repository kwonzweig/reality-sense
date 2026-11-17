# Concept sources

These rules adapt established concepts to agent decisions. The sources establish
the concepts; the effect of this particular wording requires separate evaluation.

## Resource rationality

Lieder and Griffiths describe rational cognition as a tradeoff between the value
of a decision and the resources spent reaching it. This skill applies that idea
to investigation, clarification, safeguards, and communication. Likelihood,
consequence, and reversibility help determine which uncertainties deserve effort.

Source: [Resource-rational analysis: Understanding human cognition as the optimal use of limited computational resources](https://cocosci.princeton.edu/papers/liederresource.pdf), Behavioral and Brain Sciences 43, e1 (2020).

## Double-loop learning

Argyris distinguishes correcting an action within an existing framework from
examining the governing assumptions and rules themselves. A bad result may reveal
a faulty criterion, or a failure to use an appropriate one. Investigation must
distinguish these before proposing a change. A single output can suggest an
explanation; observable behavior and comparisons test it.

Source: Chris Argyris, [Teaching Smart People How to Learn](https://hbr.org/1991/05/teaching-smart-people-how-to-learn), Harvard Business Review (1991), with an [authoritative article copy hosted by the University of Georgia](https://www.libs.uga.edu/reserves/docs/main-archive/2022/main-fall2022/han-eadu8410e/w6_argyris-teaching-smart-people-how-to-learn.pdf).

## Evidence synthesis

Evidence synthesis combines and evaluates sources to answer a defined question.
Here it guides the weight given to independent reports, their relevance to the
user's circumstances, and the scope of a conclusion. These lightweight rules
also preserve the original skill's practices for adoption counts and symmetrical
comparison. They do not constitute a systematic review protocol.

Source: Cochrane, [Summarizing study characteristics and preparing for synthesis](https://www.cochrane.org/authors/handbooks-and-manuals/handbook/current/chapter-09).

## Single source of truth

A single source of truth masters each data element in one place, and other
systems reference it instead of keeping their own copy. Copies that are kept and
updated need reconciliation, and duplicates risk returning outdated values. Hunt
and Thomas state the same idea for code as DRY: each piece of knowledge has one
authoritative representation. Hard coding, which embeds data in a program instead
of obtaining it from an external source at runtime, is the most direct way to
make such a copy. A runtime cache stays on the right side of this line when it
follows the cache-aside pattern: it loads data from the store on demand and
expires it, so the store remains the owner.

Sources: Wikipedia, [Single source of truth](https://en.wikipedia.org/wiki/Single_source_of_truth)
and [Hard coding](https://en.wikipedia.org/wiki/Hard_coding); Andrew Hunt and David
Thomas, *The Pragmatic Programmer* (1999); Azure Architecture Center,
[Cache-Aside pattern](https://learn.microsoft.com/en-us/azure/architecture/patterns/cache-aside).

## Existing authoring workflows

Skill Creator, writing-skills, and systematic-debugging already cover scoped
changes, evidence, baseline comparisons, and diagnosis. Use those workflows when
available and applicable to the task. Practical Judgement supplies decision
criteria across tasks and has no mandatory dependency on another skill.

For example, [Anthropic's Skill Creator](https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md#how-to-think-about-improvements)
explicitly calls for generalizing feedback beyond a few examples. [Superpowers](https://github.com/obra/superpowers)
provides writing-skills and systematic-debugging. Availability and a reminder to
read them are separate from demonstrating that their guidance affected an edit.
