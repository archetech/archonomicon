# Archonomicon
The [Archetech](https://archetech.com) Nomicon

**1.** The name of the [game](Nomicon/README.md) is Archonomicon.

**2.** The goal of the game is to decentralize the singularity. #immutable

**3.** A proposal MUST NOT be adopted while any player objects to it. #immutable

**4.** Proposals may add, amend or repeal a rule. #immutable

**5.** All rules should be logically self-consistent.

## Players

**6.** The players of the game are listed in [players.md](players.md). #immutable

**7.** A person becomes a player when a proposal adding them to the list is adopted.

**8.** A player may leave the game at any time by announcing it in the game repository, after which the Operator MUST remove them from the list.

## Proposals

**9.** The rules of the game are the text of the default branch of the [game repository](https://github.com/archetech/archonomicon), except for records that the rules direct the Operator to keep, such as the list of players. Updating such a record as the rules direct is not a rule change. #immutable

**10.** A proposal is a pull request to the game repository that adds, amends or repeals rules.

**11.** Anyone MAY submit a proposal, but only the agreement and objections of players count toward its adoption.

**12.** The Operator is the player who maintains the game repository and carries out the provisions of the rules that are not yet automated. The Operator is [macterra](https://github.com/macterra).

**13.** A proposal is adopted when the Operator merges it. By merging a proposal, the Operator certifies that it met the conditions for adoption in the rules. #immutable

**14.** A proposal MUST state the change and the reason for it. It SHOULD also state the alternatives considered and its effect on compatibility and security in the projects under jurisdiction.

**15.** A player agrees to a proposal by approving its pull request. A player who submits a proposal agrees to it by submitting it, and the Operator's merge counts as the Operator's agreement. #immutable

**16.** An agreement applies only to the text of the proposal as it was when the player approved it. If the proposal changes after that, the earlier agreement no longer counts. #immutable

**37.** A proposal MAY be merged once it has been open for at least 7 days, or sooner if every player has agreed to it. If the proposal changes, the 7 days start again from the change. #immutable

**38.** A player objects to a proposal by requesting changes on its pull request. The objection stands until the player withdraws it, by approving the proposal or dismissing their review. #immutable

**17.** The adopted text of a proposal is exactly the text merged. A proposal closed without merging is not adopted; it MAY be submitted again.

**18.** An adopted rule change takes effect when it is merged and does not apply to anything that happened before then.

**19.** Every change made to the game repository before this rule was adopted, including [Proposal #1](https://github.com/archetech/archonomicon/pull/1), is ratified as a validly adopted rule change.

## Immutable rules

**39.** A rule MAY carry tags, written as hashtags after its text, such as #immutable. Tags are not part of a rule's text, and a tag has only the effect that a rule gives it. #immutable

**40.** A rule tagged #immutable is immutable, and every other rule is mutable. An immutable rule MUST NOT be amended or repealed. Adding or removing the #immutable tag is a transmutation. A transmutation proposal MUST do nothing else and MUST NOT be adopted without the agreement of every player. This rule takes precedence over rule 4. #immutable

**41.** The Operator MUST NOT merge a proposal that would make it impossible to adopt further proposals. #immutable

## Succession

**33.** The backup Operator is [Flaxscrip](https://github.com/Flaxscrip).

**34.** If the Operator has not merged, reviewed or commented in the game repository for 28 days, any player MAY ask the Operator to respond, in an issue in the game repository. If the Operator does not respond within 7 days of that request, or announces that they cannot act, the backup Operator acts as Operator, with all of the Operator's powers and duties, until the Operator announces their return in the game repository or a proposal names a new Operator. This rule takes precedence over rule 12.

**36.** The Operator SHOULD keep a record, which the backup Operator can reach, of how to obtain the access needed to act as Operator.

## Jurisdiction

**20.** Only [Ulex 1.1](https://github.com/proftomwbell/Ulex/tree/master/versions/1.1) governs any claim or question arising under or related to this agreement, including the proper forum for resolving disputes, all rules applied therein, and the form and effect of any judgement.

**21.** Projects that fall under the jurisdiction of Archonomicon:

* [Archon](https://github.com/archetech/archon)
* [Archon schemas](https://github.com/archetech/schemas)
* [Sigil](https://github.com/archetech/sigil)
* [did:cid specifications](https://github.com/archetech/didcid-specs)

**22.** A project is added to or removed from the list in rule 21 only by an adopted proposal.

**23.** Changes to a project's repository are not rule changes. They are made through the project's own development process, and they MUST comply with the rules of the game.

**24.** A project MAY keep its own rules in its repository, such as contribution guidelines or instructions for coding agents. Project rules MUST NOT conflict with the rules of the game, and where they do, the rules of the game prevail.

## Protocol

**42.** The protocol implemented by the projects under jurisdiction is defined by the [did:cid specification](https://github.com/archetech/didcid-specs). Every implementation of it in those projects MUST conform to the specification.

**43.** A difference between an implementation and the specification, or between two implementations, is a defect. It MUST be corrected in the implementation, unless the specification is silent or in error, in which case the specification MUST be corrected first.

**44.** If an implementation is found to depend on behaviour that affects which operations are accepted or how a DID resolves, and the specification does not describe that behaviour, it MUST either be described in the specification with a test vector or be removed from the implementation.

**45.** A change to the protocol is made by changing the specification. The change is Proposed when the specification describes it and signed test vectors for it, published in a project under jurisdiction and referenced by the specification, are passed by every implementation. It is Deployed when every implementation has released it and run it on the live network without diverging. An implementation MUST NOT release a protocol change before it is Proposed. The specification MUST record the status of each change.

**46.** Every protocol change MUST be backwards compatible: every history the network has accepted MUST resolve the same after the change as before it. The specification MUST record how this was shown, either by construction or by an audit of retained histories that states what it covered. A change that cannot be shown to be backwards compatible MUST NOT be made unless a proposal adopted under these rules approves it.

**47.** Correcting an implementation to conform to the specification, or correcting the specification where it misdescribes behaviour that every implementation shares, is not a protocol change.

## Precedence

**29.** If two rules of the game conflict, an immutable rule prevails over a mutable one. Otherwise, a rule that explicitly claims precedence over the other prevails. Otherwise, or if each claims precedence over the other, the rule with the lower number prevails. #immutable

**31.** Rule 29 applies only to the rules of the game. It does not change how Ulex 1.1 resolves conflicts among its own provisions under rule 20.

**32.** When it is unclear how a rule applies, the Operator decides how to apply it until a proposal resolves the question. This does not limit a player's recourse to Ulex 1.1 under rule 20. A conflict or ambiguity found in the rules SHOULD be resolved by a proposal.

## Conventions

**25.** The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

**26.** Each rule has a permanent number, which is how it is cited (for example, "rule 13"). A rule's number says nothing about where it appears: rules MAY be moved between sections, and sections added, split or reordered, without changing any number. #immutable

**27.** A new rule takes the next number after the highest number ever assigned. An amended rule keeps its number. #immutable

**28.** A number is never reused. When a rule is repealed, it is removed from the ruleset and recorded, with its number and its last text, in [repealed.md](repealed.md). #immutable
