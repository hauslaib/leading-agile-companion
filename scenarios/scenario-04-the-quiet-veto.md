# Scenario 04: The quiet veto

## Setup

An ART has been working for three PIs on a platform initiative that requires sign-off from the head of an adjacent function (call him D.) whose group owns a downstream system the initiative integrates with. D. has never said no to the initiative. He has also never said yes.

The pattern, viewed across nine months:

- D. attends solution train syncs roughly half the time. When he attends, his contributions are procedural ("we'll need to review that against the integration standards") rather than substantive.
- Sign-off requests from the ART are met with requests for additional documentation, then with requests for revisions to the documentation, then with calendar conflicts when sign-off meetings are proposed.
- Engineers on the ART have stopped asking when integration will be approved. They have started building workarounds that don't need D.'s sign-off, which the architect has flagged as accumulating technical debt.
- D.'s direct reports, in informal conversations, have indicated that D. has concerns he has not articulated in any meeting the RTE has been part of.
- D. is widely respected. He has been at the company for fifteen years. His group's quality record is excellent.

The RTE raised the dependency in their last quarterly review with the STE. The STE escalated it, gently, to D.'s peer in the leadership group. The peer's response was that "D. moves carefully" and that "nothing is being blocked".

In the most recent PI planning, three teams declined to take dependencies on the integration because the integration's status remained unclear. The platform initiative is now meaningfully behind where the architect believed it would be by this point.

## The tensions in play

- **Absence as a position.** D. has not refused anything. Naming the pattern requires saying that the absence of a yes *is* a no, which D. will reasonably contest.
- **Earned conservatism.** D.'s carefulness is part of why his group's quality record is strong. Asking him to move faster is asking him to move differently, and he has fifteen years of evidence that his way works.
- **Workaround as adaptation.** The teams' workarounds are rational at the team level and corrosive at the architectural level. Stopping the workarounds before resolving the dependency makes things worse.
- **Reputation gravity.** D. has standing the RTE does not have, and the STE has only partially. Direct confrontation is asymmetric in a way the RTE will lose.
- **The unspoken concern.** D.'s direct reports have hinted that he has unarticulated concerns. Until those are surfaced, every intervention is being aimed at the wrong target.

## What is *not* the problem

- D.'s competence or intent. He is not sabotaging anything. He is operating consistently with his standards and his pace.
- The integration design. It has been reviewed by the architect and is sound.
- The teams' ability to deliver. They are blocked on a decision, not on capability.
- The escalation that already happened. It produced the response it was going to produce, and going back through the same channel will produce the same response.

## Discussion prompts

1. The clearest description of the situation involves saying that D. is blocking the work without saying so. Is that a description the RTE can put in writing? What changes if it is written down versus only spoken?
2. D.'s direct reports have signalled that he has unarticulated concerns. What are the legitimate ways to surface those, and what are the ways that would damage the RTE's relationship with both D. and his reports?
3. The teams' workarounds are creating debt. Is the right move to stop the workarounds (forcing the dependency to bite), or to continue them and document the cost? Defend your answer.
4. The STE's escalation got a polite deflection. What would a second escalation need to look like to produce a different result, and what is the cost of making it?
5. D. has been at the company for fifteen years. The RTE has been in role for eleven months. What does that asymmetry mean for the kinds of conversation that are available to the RTE versus the kinds that are not?
6. Imagine a version of this where D. is right: there is a real concern with the integration that he has not been able to articulate, and the workarounds are accumulating risk that will surface badly. What would the RTE need to do differently to discover that?

## Facilitator notes

This scenario reliably surfaces a divide in how participants think about organisational power. One group will frame D. as a problem of misuse: he has authority and is using it passively to obstruct work he hasn't justified obstructing. Another group will frame him as a signal: careful people who go quiet usually have a reason, and the work of the RTE is to find it before assuming bad faith. Both readings are defensible from the setup.

The richest discussions happen when participants are pushed to articulate what evidence would shift them from one framing to the other. Many will not have thought about it.

A common trap: the proposed intervention is "have a direct conversation with D.". This is rarely wrong but is almost always insufficient on its own. The conversation can only succeed if it is not the first move. The RTE has to have already done enough work to know what to ask, and the conversation has to be positioned as an offer to remove a blocker rather than a request for an explanation.

Another trap: framing this as a process problem fixable with a RACI or an integration governance board. Those interventions can work, but only after the underlying concern is named. Building governance around an unspoken disagreement entrenches it.

Pair with the stakeholder-tension grid (`worksheets/stakeholder-tension-grid.md`) to map D.'s position relative to the RTE, the STE, and the architect, and to make explicit the differences in standing that constrain what each can say.

## Variations

- **D. has a peer who has the same concerns and is willing to say so.** The RTE now has a way into the substance of the disagreement that does not require D. to be the one who articulates it.
- **D. is six months from retirement.** The calculation about how much energy to invest in shifting his position changes, and so do the ethics of doing so.
- **The integration is on the critical path for a regulatory deadline.** Time pressure forces the implicit veto into the open, which may resolve the situation at the cost of a relationship.
