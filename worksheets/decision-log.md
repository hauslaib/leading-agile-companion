# Decision log

A lightweight format for capturing decisions made in conditions of disagreement. The log is not a meeting minutes template and not a project tracker. It is the record you want to have when someone asks, six months later, why this was decided the way it was.

The log is opinionated about one thing: every decision worth recording involves something that was not chosen. Most decision records omit the not-chosen, which is exactly what makes them useless when the decision is revisited.

---

## When to log a decision

Not every decision needs to be logged. Use this format when at least one of the following is true:

- The decision was made under disagreement that is not fully resolved.
- The decision deprioritises something that another party committed to.
- The decision relies on assumptions that may not hold.
- The decision will be revisited if conditions change, and the conditions can be named.
- Future participants who were not in the room will need to understand it.

If none of these apply, a one-line note in the team's working channel is enough. Logging routine decisions devalues the log.

---

## Decision record

### Decision ID

A short identifier. Suggested format: `YYYY-MM-DD-short-slug`. Example: `2026-04-29-defer-platform-refactor`.

### Title

One sentence. The title should describe the decision, not the discussion. *"Defer platform refactor to PI-3"* is a title; *"Discussion of platform priorities"* is not.

> *(write here)*

### Status

One of: `proposed`, `decided`, `superseded`, `revisited`. Use `proposed` for decisions still under discussion that you want to log in advance. Use `superseded` to mark records that are no longer current; do not delete them. Use `revisited` to mark a decision that was reopened, with a link to the new record.

> *(write here)*

### Date

The date the decision was made, not the date of the meeting in which it was discussed if the two are different.

> *(write here)*

---

### What was decided

Two to four sentences. State the decision in operational terms: what changes, for whom, starting when. Avoid hedging language; if the decision is hedged, the hedges go in *constraints* below, not in the statement itself.

> *(write here)*

### What was not decided

Equally important. List the questions that were raised in the discussion and were *not* resolved by this decision, even if they touch the same topic. The not-decided list is what prevents the log from being read later as more authoritative than it is.

> *(write here)*

> *(write here)*

### What was deprioritised

If anything was given up to make this decision, name it. Be specific about what was deprioritised, who was committed to it, and how they were informed.

| Item deprioritised | Who was committed to it | How they were informed |
|---|---|---|
| | | |
| | | |

If this section is empty, double-check. Most non-trivial decisions deprioritise something. An empty section often means the deprioritisation was implicit, which is the most common failure mode of decision-making under disagreement.

---

### Who decided

Name the person or group with authority for this decision. Distinguish:

- **Decided by.** The party with formal authority.
- **Consulted.** Parties whose input shaped the decision.
- **Informed.** Parties told after the fact.
- **Dissented.** Parties who participated, were heard, and did not agree with the outcome.

| Role | Names |
|---|---|
| Decided by | |
| Consulted | |
| Informed | |
| Dissented | |

The *dissented* row is a deliberate inclusion. Disagreement that is named and recorded does not need to be re-litigated; disagreement that is suppressed reappears later as resistance. Naming the dissent does not require justifying it.

---

### Constraints and assumptions

The conditions under which this decision is the right one. Be concrete. Vague assumptions ("market conditions remain stable") are not actionable; specific ones ("we retain the four engineers currently allocated to ART B") are.

> *(write here)*

> *(write here)*

### When this should be revisited

A trigger or a date. Either is acceptable. Both are better.

- **Trigger:** *(condition that, if it occurs, requires this decision to be reopened)*
- **Date:** *(latest date by which this decision should be reviewed regardless of triggers)*

---

### Cost of the decision

This section is often skipped and rarely should be. Costs come in three categories:

1. **Direct.** What the decision costs in time, money, or capacity.
2. **Relational.** What it costs in trust or standing with parties affected.
3. **Optionality.** What it forecloses that was previously available.

A short note on each is enough.

> **Direct:** *(write here)*
>
> **Relational:** *(write here)*
>
> **Optionality:** *(write here)*

---

### Links

References to related artefacts. Common ones:

- Conflict map for the situation that produced the decision.
- Stakeholder tension grid showing the parties involved.
- Earlier decision records superseded or extended by this one.
- The retrospective or planning event in which the decision originated.

> *(write here)*

---

## How to use the log

- Keep records short. A record longer than one printed page is usually doing too much.
- Write the record close to the decision, not days later. Memory of who said what at the boundary of the decision degrades quickly.
- Review the log at quarterly intervals. The records most worth re-reading are the ones whose triggers have not yet fired.
- Do not edit a closed record to make it look better. Mark it `superseded` and write a new one.
- The log is a working artefact, not a deliverable. Resist pressure to make it look polished.

For an example of a completed decision record, see `examples/decision-log-filled.md`.
