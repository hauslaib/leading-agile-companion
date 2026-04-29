# Retrospective format: The pre-mortem retro

## When to use this

Use this at the end of a PI when the team has met its objectives and is preparing to plan the next one. It is poorly suited to PIs that ended badly. Failure produces enough material on its own and does not need a hypothetical layer.

The format works best when the team is somewhat satisfied with the PI just completed. Satisfaction is the condition the format exploits: teams that have done well are more candid about what they almost missed.

Allow 90 minutes. This format compresses poorly.

## What this is for

The session combines a retrospective on the completed PI with a pre-mortem of the next one, structured around a single question: *"Imagine the next PI ends in failure. What did we ignore in this retrospective that caused it?"*

The format treats the retrospective as a mechanism that can itself fail. Most retrospectives surface things that are easy to name. The dangerous things are the ones the team has reasons not to name, and the pre-mortem framing gives those reasons less protection.

## What you need

- A whiteboard or wall, divided into three regions: **What worked**, **What we almost lost**, and **What we are not yet seeing**.
- A facilitator who can hold the room in the speculative frame without letting the discussion collapse into reassurance or alarm.
- A timeboxed agenda. The format depends on transitions happening on time; lingering in any one phase weakens the next.

## Format

### Phase one: the standard retro, 25 minutes

Run the team's normal retrospective format briefly: Start/Stop/Continue, 4Ls, whatever the team is used to. Keep it short. The point is not to do a thorough retrospective; the point is to produce a baseline of what the team would have said if the pre-mortem layer were not added.

Capture the output on the **What worked** side of the wall. Do not curate it. Move on.

### Phase two: the near-miss, 20 minutes

The facilitator asks: *"What worked this PI that almost did not? Identify two or three things that came close to failing and recovered."*

Examples: a delivery that depended on one engineer being available in the final week. A stakeholder review that went well because a particular question was not asked. An integration that succeeded because a workaround held longer than expected.

Capture these in the middle region, **What we almost lost**. The recovery in each case is interesting; the conditions that made the recovery possible are the data the team is mining.

### Phase three: the pre-mortem, 30 minutes

This is the substantive part. The facilitator opens with the framing question, slowly: *"Imagine it is the end of the next PI. The PI failed. We are sitting in the same room having this same conversation, except the failure has already happened. What did we ignore in this retrospective that caused it?"*

Allow silence for at least thirty seconds. Do not fill it.

The team identifies items for the **What we are not yet seeing** region. The items take three typical forms:

1. **Continuations of near-misses.** "The thing that almost failed this PI fully fails next PI because the conditions worsen." Useful and easy to name.
2. **Disagreements not surfaced.** "We did not address X this PI, and X gets worse next PI." Harder to name; the format depends on these surfacing.
3. **External assumptions.** "We assumed the customer would stay engaged, the executive would hold their position, the team composition would not change." Often the most consequential and the easiest to dismiss in the moment.

The facilitator's job is to keep the conversation in the imagined-failure frame. Participants will repeatedly slip into reassurance ("but we have a mitigation for that"). The facilitator gently returns the question: *"In the imagined failure, the mitigation did not work. Why not?"*

### Phase four: the carry-forward, 15 minutes

From the **What we are not yet seeing** region, the team selects no more than two items to actively address in the coming PI. The selection is not by vote. It is by a single criterion: which two, if ignored, would the team most regret in three months?

For each selected item, the team names:

1. Who owns watching it.
2. What signal would indicate the imagined failure is becoming real.
3. When the team will revisit it.

Items not selected are documented in the team's retro log. They are not discarded. The pre-mortem retro often produces a richer parked-items list than action items, and the parked items are frequently the source of the next PI's planning conversations.

## Facilitation notes

The pre-mortem framing is fragile. Two failure modes recur.

The first is the team treating the framing as a creative exercise and producing entertaining-but-unserious failure scenarios. The facilitator's response is to ask, of any item: *"Is this something that could happen, or something that would make for a good story?"* The distinction is usually clear once asked.

The second is the team treating the framing as a threat assessment and producing a comprehensive list of risks. This is well-intentioned and unhelpful; a long list of risks is a way of avoiding the harder question of which risks the team is currently choosing not to see. The facilitator's response is to constrain the count: no more than five items in the **What we are not yet seeing** region. The constraint forces selection, and selection forces the team to acknowledge what it is prioritising.

A useful prompt mid-session: *"If we had run this retrospective at the end of the previous PI, what is on the wall right now that should have been on the wall then?"* The answer is often illuminating.

The format is more demanding for the facilitator than a standard retro because the speculative phase requires actively holding the frame against the room's instinct to leave it. Facilitators new to the format should run it once with a co-facilitator before running it solo.

## What this format does not do

- It does not predict the actual failure mode of the next PI. The items surfaced are the ones the team can imagine; the actual failure is often something no one in the room could have named.
- It does not replace risk management. Pre-mortems and risk registers are different artefacts. Items from this session that warrant formal tracking should be moved to the appropriate register and managed there.
- It does not work well as a recurring quarterly format. The first run produces strong material. The second run, six months later, also tends to. Running it every PI exhausts the format and produces diminishing returns.

## Pairing

Pair with the decision-log worksheet (`worksheets/decision-log.md`) for items that warrant a recorded decision about how the team will respond if the imagined failure begins to materialise.

## Variations

- **Solution train scope.** Run the format with the RTEs and the STE rather than a single team. The pre-mortem question shifts to coordination failures rather than execution failures, and the surfaced items are usually about communication and dependency management.
- **After a successful release.** Run the format two weeks after a major release rather than at the end of a PI. The hindsight is sharper and the near-misses are easier to name while still recent.
- **Before a planning event.** Run a stripped-down version of the format (45 minutes) the week before PI planning, focused only on the **What we are not yet seeing** region. This produces useful planning input without the full retrospective layer.
