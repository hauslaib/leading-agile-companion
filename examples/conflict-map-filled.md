# Conflict map: example

A worked example of the conflict map worksheet (`worksheets/conflict-map.md`), filled in against Scenario 01: *Misaligned product and architecture*. The example is one possible filled version, completed by a hypothetical STE in week six of the PI. It is not the model answer; it is one practitioner's reading of the situation in enough detail that the format is unambiguous.

---

## 1. The presenting situation

Six weeks into the PI, three teams across two ARTs have missed the first checkpoint of their PI objectives. Reviewing the misses with the RTEs, the reasons given by the product owners and the tech leads for the same teams contradict each other. Both the product management group and the system architecture group presented commitments at the start of the PI that, on inspection, cannot both be delivered without descoping. Neither group has formally raised the conflict; both are operating as if their plan is the agreed plan.

---

## 2. The parties

| Party | Role in the situation | What they are protecting | Authority |
|---|---|---|---|
| Head of Product (HoP) | Sets the customer-facing feature commitments for the PI | Customer outcomes and the product team's credibility with stakeholders | Partial |
| Head of Architecture (HoA) | Drives the platform refactor across the trains | Long-term system health and architectural decisions made over the previous PI | Partial |
| RTE (ART A) | Surface-level coordination across three teams primarily aligned with HoP's plan | Their teams' delivery commitments and morale | Partial |
| RTE (ART B) | Surface-level coordination across two teams primarily aligned with HoA's plan | Same as ART A's RTE | Partial |
| STE (me) | Cross-train coordination | The credibility of the solution train as a coordination mechanism | Partial |
| Director of Engineering | Line manages HoP, HoA, and STE | Quarterly delivery commitments to the executive group | Full (rarely uses it) |
| Affected teams | Doing the work | Their own coherence and the avoidance of being whipsawed | None |

---

## 3. The tensions

| Tension | Sides | Legitimate or constructed? |
|---|---|---|
| Customer outcomes vs. platform health | HoP vs. HoA | Legitimate |
| Visible vs. invisible work | Feature delivery (HoP) vs. refactor (HoA) | Legitimate |
| Authority over PI scope | Product owns *what*; Architecture owns *how*; the boundary is undefined | Constructed |
| Speaking up vs. coping silently | Teams choosing sides quietly vs. surfacing the conflict | Constructed |
| Sunk-cost momentum | Both groups have invested for weeks and treat stopping as waste | Constructed |

The constructed tensions are where the leverage is. The legitimate ones are real and will need to be traded off; arguing them as if one side should win produces only fatigue.

---

## 4. What is *not* the problem

- The teams' execution capability. They are doing what they can with conflicting inputs.
- The PI planning event. The misalignment predates planning; planning surfaced it without resolving it.
- Either group's intent. Neither HoP nor HoA is acting in bad faith.
- The product roadmap or the architectural roadmap as artefacts. Both are coherent in isolation. The problem is they cannot both be executed at the same time at current capacity.

---

## 5. What you do not yet know

| What you don't know | How you might learn it | Cost of asking |
|---|---|---|
| Whether HoP and HoA have spoken about this directly | Ask either, individually | Low; reveals quickly whether the disagreement is being avoided |
| Whether the Director of Engineering knows | Ask the Director | Medium; the question implies the train is not handling it |
| What the affected teams would actually descope if asked | Run a short, structured question with each tech lead | Low to medium; but only useful if their input is going to influence the outcome |
| Whether any of the platform refactor work has external dependencies (regulatory, vendor) | Architect's documentation; HoA directly | Low |

The fourth question is the one I have been avoiding because the answer might force a different conversation entirely. It goes on the list.

---

## 6. Your standing

| Component | Rating | What would strengthen it |
|---|---|---|
| Authority | Moderate | Formal STE remit covers cross-train coordination; does not extend to telling either group what to deliver |
| Relationship | Moderate with HoP, weaker with HoA | Two more substantive 1:1s with HoA before convening anything |
| Information | Strong on the symptom; moderate on the substantive disagreement | Talk to two of the team tech leads before any leadership conversation |

Reading: relationship with HoA is the weakest component. A joint workshop now would land badly because HoA does not yet trust me to convene fairly. Strengthen the relationship first; the workshop is the second move, not the first.

---

## 7. The intervention you are considering

> **Your intervention:**
>
> Hold separate 30-minute conversations with HoP and HoA over the next week, framed as a request for help understanding the gap between their plans. Then propose a joint working session, scheduled for week 8, to make explicit decisions about descope.
>
> **If it works:**
>
> The two groups arrive at the joint session with their disagreements articulated, neither feeling ambushed. A descope decision is made and recorded in the decision log. The teams stop receiving conflicting prioritisation signals by week 9.
>
> **If it fails:**
>
> One or both of HoP and HoA experiences the 1:1 as the STE taking sides. The joint session does not happen, or happens as a polite re-statement of original positions. The teams continue absorbing the conflict for the rest of the PI, and the failure mode escalates to the Director by week 10, at which point the conversation happens with less of my framing and more of theirs.
>
> **Cost regardless:**
>
> Two hours of preparation, two 30-minute meetings, one 90-minute joint session. Some standing with the Director if the joint session does not produce a clean outcome. Some standing with the affected teams if they continue to absorb the conflict during weeks 6–8.

---

## 8. The conversation you are avoiding

> The conversation with the Director of Engineering about the fact that the boundary between Product and Architecture authority over PI scope has been unclear for at least two PIs, and that the current situation is the predictable result of leaving it unclear. The conversation is uncomfortable because the Director is the one who could have addressed the boundary and has not, and naming this risks being heard as assigning blame upward. It is also the conversation most likely to produce a structural change rather than a one-off resolution.

---

*This example is illustrative. The same scenario, filled in by a different STE, would produce a recognisably different worksheet. That is the format working as intended.*
