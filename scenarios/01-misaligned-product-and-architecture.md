# Scenario 01 — Misaligned product and architecture

## Setup

A solution train of four ARTs is six weeks into a new PI. The product management group has committed to a customer-facing feature set built around a new user-flow concept. The system architecture group, working largely in parallel during the previous PI, has been investing in a platform refactor — splitting a legacy monolith into three services — that they consider a precondition for the next two years of work.

Both groups present at the solution train sync. Both believe their plan is the plan. Neither plan can be fully delivered in the PI without compressing or descoping the other. Engineering teams are receiving conflicting prioritisation signals from their product owners and their tech leads, and several have quietly started working on whichever item the loudest voice that week pushed for.

The STE notices the symptom in week six: three teams have missed their PI objectives' first checkpoint, and the reasons given by the product owner and the tech lead for the same team contradict each other.

## The tensions in play

- **Customer outcomes vs. platform health.** Both are legitimate. Neither group is wrong about what they are protecting.
- **Visible vs. invisible work.** Feature delivery is demoable; architectural refactors are not. Stakeholders reward what they can see.
- **Authority ambiguity.** Product management owns the *what*; architecture owns the *how*. The boundary between them was never explicitly negotiated for this PI.
- **Team-level coping.** Teams have absorbed the conflict by silently choosing sides, which masks the disagreement at the leadership level and makes it look like execution is the problem.
- **Sunk-cost momentum.** Both groups have been working on their plan for weeks. Stopping either feels like waste.

## What is *not* the problem

- The teams' execution capability. They are doing the best they can with contradictory inputs.
- The PI planning process itself. The misalignment predates planning; planning surfaced it without resolving it.
- Either group's competence or intent. Both are doing their jobs as they understand them.

## Discussion prompts

For coaching sessions, training, or reading groups. There are no model answers. The value is in the disagreement that surfaces while working through them.

1. Whose problem is this to solve? The STE? The two group leads? Someone above all three? Defend your answer.
2. The STE's first instinct might be to call a joint workshop between product and architecture. What are the failure modes of that move? What would have to be true for it to work?
3. How much of this could have been prevented in PI planning, and how much is structural, i.e., would have shown up regardless of how planning went?
4. The teams have started silently choosing sides. Is that a behaviour to correct, or a signal to listen to? What does it tell you about which group has more organisational gravity?
5. If you had to descope something this week, what would you cut, and how would you frame the cut to the group whose work is being deprioritised?
6. What would you put in place so this specific misalignment is visible *before* week six in the next PI?

## Facilitator notes

This scenario tends to split a room. Some participants will frame it as a governance failure (RACI, decision rights). Others will frame it as a relational failure (the two leads don't trust each other). Both framings are partially right and lead to different interventions. Resist the urge to consolidate the discussion toward one framing too early -- the productive disagreement is the point.

A common trap: participants propose "align on shared OKRs" as the solution. Push back. Shared OKRs that are written *after* the conflict are usually negotiated artefacts that paper over the underlying disagreement rather than resolving it. Ask what the OKRs would actually say, and watch the disagreement re-emerge.

If using this in a workshop, allow 45–60 minutes. Pair with the conflict-map worksheet (`worksheets/conflict-map.md`) for participants to externalise the tensions before discussing.

## Variations

- **Higher stakes:** the platform refactor is being driven by a known security vulnerability with a regulatory deadline.
- **Lower stakes:** the platform refactor is a quality-of-life improvement with no external pressure.
- **Personnel change:** one of the two group leads is new in role, three weeks in.

Each variation shifts the balance of legitimacy and changes which interventions are reasonable. Worth running the scenario twice with different variations if time allows.
