# Scenario 05: The dependency that wasn't there

## Setup

Two ARTs in the same solution train have a dependency that has been on the program board for the entire PI. ART A is building a feature that requires an API exposed by a service owned by ART B. The dependency was discussed at PI planning, both RTEs were in the room, and the agreed delivery date for the API was the end of iteration 4.

In iteration 5, ART A's team begins integration testing and discovers that the API does not exist. ART B's RTE is contacted. His response is that the API was deprioritised in iteration 2 in favour of a hotfix programme that came down from operations, and that the change was communicated.

ART A's RTE has no record of the change. ART B's RTE has a Slack message in a channel that ART A's RTE was not in, and an entry in a release notes document that was distributed to ART B's stakeholders only. He believed this constituted notification.

The STE was at the iteration 2 solution train sync and does not recall the deprioritisation being raised. Reviewing the notes from that meeting, the topic appears as a single line in a status update: *"hotfix programme prioritised; commitments revisited"*. No specific dependency was named.

ART A now has an unfundable feature in the PI, three teams that planned around its delivery, and a stakeholder who has been told the feature is on track. The PI has four iterations remaining.

The two RTEs are professional with each other in front of the STE and visibly less so in private. ART B's RTE believes he followed the process he was given. ART A's RTE believes the process is broken if it allows this to happen.

## The tensions in play

- **Both versions are partially true.** ART B's RTE did communicate. ART A's RTE did not receive the communication in a form he could act on. The mismatch is structural, not personal, but the people involved are taking it personally because the consequences are personal.
- **Process literalism vs. process intent.** Following the letter of a coordination process while missing its purpose is a recurring pattern in mature organisations. Naming it without sounding sanctimonious is hard.
- **Recovery cost is asymmetric.** ART A pays nearly all the recovery cost. ART B paid the cost in iteration 2 by absorbing the hotfix programme. There is no mechanism currently to balance these.
- **Trust between the two trains is now lower.** Whatever decision is made about the immediate PI will be filtered through this lower-trust state in the next two PIs unless something is done explicitly to repair it.
- **The STE's role in the original failure.** The STE was in the room when the change was glossed over. Acknowledging that without performative self-blame is part of resolving the trust issue.

## What is *not* the problem

- Either RTE's competence or intent. They are doing their jobs.
- The hotfix programme. It was real, urgent, and the right thing to absorb.
- The PI planning event. The dependency was identified there correctly. The failure happened later.
- The stakeholder's expectation. It is unrealistic now, but it was reasonable when it was set.

## Discussion prompts

1. Who is accountable for this failure? List every party with some share of accountability and assign a rough percentage. Then defend your numbers without changing them.
2. ART A's RTE wants to escalate. ART B's RTE wants to move on. The STE has to choose a stance for the next solution train sync. What stance lets the failure be discussed without making either RTE defensive?
3. The communication did happen, in a channel and a document that did not reach ART A. Is the right fix a better channel, a better practice, or an acceptance that some failures of this kind are unavoidable in a four-train solution? Defend your answer.
4. The stakeholder for ART A's feature has been told the feature is on track. Who tells the stakeholder it is not, when, and in what framing? What does the framing reveal about how the train manages bad news?
5. The trust between the two trains is now lower. Naming this in a meeting risks making it worse. Not naming it lets it persist. What is the version of naming it that is most likely to repair rather than entrench?
6. In the next PI planning, what mechanism would have to exist for a mid-PI deprioritisation of this size to be visible to every train that depends on it? Sketch the mechanism in three sentences. Then identify what it costs to operate.

## Facilitator notes

This scenario tends to surface participants' theories of organisational communication. Some will frame the failure as a process gap (the right channel did not exist, or was not used). Others will frame it as a relational gap (ART B's RTE should have walked over and said it). Both framings are correct in different proportions, and the right intervention usually combines the two: a process that creates the prompt for a relational conversation, rather than one that replaces it.

A trap to watch for: the proposed solution is "all dependency changes go through the STE for approval". This sounds reasonable and is almost always too brittle to last beyond the PI it was created in. STEs cannot be the sole bottleneck for cross-train coordination at any meaningful scale; the proposal usually reveals itself as wishful thinking within two iterations. Push participants to design a mechanism that does not require heroics.

Another trap: framing this as a teaching moment for ART B's RTE. The setup is sympathetic to ART A, and participants will want to assign blame. Resist. The structural failure is more interesting than the individual one, and the individual failure dissolves once the structural one is named.

A useful prompt for the second half of the discussion: ask what this scenario looks like from ART B's RTE's perspective at the moment he learns ART A discovered the change in iteration 5. Most participants have not considered it.

Pair with the decision-log worksheet (`worksheets/decision-log.md`). The decision in iteration 2 to deprioritise the API existed; what was missing was a record of the dependencies it broke. The worksheet, retrofitted to that decision, illustrates what should have been written down at the time.

## Variations

- **The two RTEs report to the same line manager.** The conversation that needs to happen now has a different shape because the line manager has standing to convene it.
- **ART B has done this before.** Once is a structural failure; twice is a pattern, and the conversation needs to address the pattern rather than the instance.
- **The stakeholder is internal rather than external.** The recovery options are different, and the relational repair is harder because the stakeholder will be in PI planning conversations again next quarter.
