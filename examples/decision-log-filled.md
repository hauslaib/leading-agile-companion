# Example: Decision log

A worked example of the decision log (`worksheets/decision-log.md`), filled in against Scenario 03: *The executive promise*. The decision being recorded is the one made in week three after the executive's commitment surfaced. The example shows the format under realistic conditions where the decision is uncomfortable and partial.

---

## Decision record

### Decision ID

`2026-04-22-Q3-capability-rescope`

### Title

Reduce the Q3 capability commitment to a defined subset, with the remainder slipped to PI 4.

### Status

`decided`

### Date

22 April 2026

---

### What was decided

The Q3 capability committed to the customer at the advisory board will ship as a reduced subset covering the three highest-value user flows agreed with the customer. The remaining four flows will move to PI 4. The customer will be informed by R. directly within five business days, with HoP present. Marketing material will be revised before any public communication. The two ARTs will replan capacity for PI 3 against the reduced scope; the two PI objectives that S. had committed to a separate customer remain in scope unchanged.

### What was not decided

- Whether the original commitment process (an executive committing in a customer setting without consulting the trains) will be addressed structurally. This is on the next leadership offsite agenda.
- Whether the customer will be offered any commercial concession to absorb the slip. Account management is taking that decision separately.
- The PI 4 detailed plan for the four deferred flows.
- Whether the head of product management's role in the original commitment will be clarified to the customer. R. has been asked to handle this; the form of the handling has not been specified.

### What was deprioritised

| Item deprioritised | Who was committed to it | How they were informed |
|---|---|---|
| Four of seven user flows from the originally committed Q3 capability | The customer (via R.); the customer's advisory board representative | R. is informing the customer this week, with HoP attending |
| Approximately two weeks of platform refactor work that was scheduled for PI 3 | HoA; the architect on ART B | HoA was in the decision meeting; the architect is informed by the ART B RTE this week |

---

### Who decided

| Role | Names |
|---|---|
| Decided by | R., HoP, S., supported by the STE |
| Consulted | HoA; both RTEs; the architect on ART B; account management for the affected customer |
| Informed | The Director of Engineering; the affected ART teams (via the RTEs at the next iteration sync); marketing (via HoP) |
| Dissented | HoA dissented on the deprioritisation of platform refactor work, and asked that the dissent be recorded. He acknowledged the trade-off and agreed to support execution of the decision. |

---

### Constraints and assumptions

- The customer will accept the reduced scope without commercial concession beyond the slipped delivery date for the remainder.
- The four engineers currently allocated to the platform refactor remain available through PI 3; reassignment would invalidate the trade-off.
- No new executive-level commitments will be made on this capability before the customer conversation has taken place.
- The hotfix programme that displaced ART B's API work in iteration 2 (see decision `2026-02-11-hotfix-priority`) is fully closed by end of iteration 6.

### When this should be revisited

- **Trigger:** The customer conversation produces a request for further scope or a different timeline. Any such request reopens this decision.
- **Trigger:** Any of the four engineers on the platform refactor are reassigned for any reason.
- **Date:** Reviewed at the end of PI 3 regardless of triggers.

---

### Cost of the decision

> **Direct:** Approximately three weeks of engineering capacity already invested in the four deferred flows is parked rather than completed; some of that work remains usable in PI 4, some will need rework. The platform refactor slips by approximately two weeks against HoA's PI 3 plan.
>
> **Relational:** R.'s standing with the customer is reduced; this is partly mitigated by R. owning the conversation. HoA's trust in the train's process is reduced; the offsite agenda item on commitment governance is part of addressing this. The teams' confidence in PI commitments is unchanged on the surface and probably reduced underneath; this is being watched.
>
> **Optionality:** The PI 4 plan now has four deferred flows that were not anticipated, which constrains what else PI 4 can include. This reduces the options for the platform refactor work in PI 4 unless capacity is added.

---

### Links

- Conflict map: `examples/conflict-map-filled.md` (different scenario, different decision; included as a related artefact for the decision-making method, not for this specific decision)
- Stakeholder tension grid for the executive-level parties: held privately by the STE; not linked here
- Earlier decision: `2026-02-11-hotfix-priority` (the iteration 2 deprioritisation of the API work)
- Retrospective for PI 3, scheduled iteration 6: this decision will be revisited there

---

*This example is illustrative. The actual decision in a comparable situation would depend on details not present in the scenario, and a real decision log would be filled in by the person accountable for the record rather than by an outside facilitator.*
