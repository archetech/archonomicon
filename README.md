# Archonomicon
The [Archetech](https://archetech.com) Nomicon

**1.** The name of the [game](Nomicon/README.md) is Archonomicon.

**2.** The goal of the game is to decentralize the singularity.

**3.** A proposal MUST NOT be adopted while any player objects to it.

**4.** Proposals may add, amend or repeal a rule.

**5.** All rules should be logically self-consistent.

## Players

**6.** The players of the game are listed in [players.md](players.md).

**7.** A person becomes a player when a proposal adding them to the list is adopted.

**8.** A player may leave the game at any time by announcing it in the game repository, after which the Operator MUST remove them from the list.

## Proposals

**9.** The rules of the game are the text of the default branch of the [game repository](https://github.com/archetech/archonomicon).

**10.** A proposal is a pull request to the game repository that adds, amends or repeals rules.

**11.** Anyone MAY submit a proposal, but only the agreement and objections of players count toward its adoption.

**12.** The Operator is the player who maintains the game repository and carries out the provisions of the rules that are not yet automated. The Operator is [macterra](https://github.com/macterra).

**13.** A proposal is adopted when the Operator merges it. By merging a proposal, the Operator certifies that it met the conditions for adoption in rules 3 and 37.

**14.** A proposal MUST state the change and the reason for it. It SHOULD also state the alternatives considered and its effect on compatibility and security in the projects under jurisdiction.

**15.** A player agrees to a proposal by approving its pull request. A player who submits a proposal agrees to it by submitting it, and the Operator's merge counts as the Operator's agreement.

**16.** An agreement applies only to the text of the proposal as it was when the player approved it. If the proposal changes after that, the earlier agreement no longer counts.

**37.** A proposal MAY be merged once it has been open for at least 7 days, or sooner if every player has agreed to it. If the proposal changes, the 7 days start again from the change.

**38.** A player objects to a proposal by requesting changes on its pull request. The objection stands until the player withdraws it, by approving the proposal or dismissing their review.

**17.** The adopted text of a proposal is exactly the text merged. A proposal closed without merging is not adopted; it MAY be submitted again.

**18.** An adopted rule change takes effect when it is merged and does not apply to anything that happened before then.

**19.** Every change made to the game repository before this rule was adopted, including [Proposal #1](https://github.com/archetech/archonomicon/pull/1), is ratified as a validly adopted rule change.

## Immutable rules

**39.** Every rule is either mutable or immutable. A rule is mutable unless rule 40 lists it as immutable.

**40.** The immutable rules are rules 2, 3, 4, 9, 13, 26, 27, 28, 29, 30, 37, 38, 39, 40, 41, 42 and 43.

**41.** An immutable rule MUST NOT be amended or repealed. To change it, a proposal MUST first transmute it into a mutable rule by amending rule 40, which is the only way rule 40 may be amended. A transmutation proposal, in either direction, MUST do nothing else and MUST NOT be adopted without the agreement of every player. This rule takes precedence over rule 4.

**42.** The Operator MUST NOT merge a proposal that would make it impossible to adopt further proposals. At least one rule MUST always be mutable.

**43.** No rule may prevent a player from objecting to a proposal.

## Succession

**33.** The backup Operator is [Flaxscrip](https://github.com/Flaxscrip).

**34.** If the Operator has not merged, reviewed or commented in the game repository for 28 days, any player MAY ask the Operator to respond, in an issue in the game repository. If the Operator does not respond within 7 days of that request, or announces that they cannot act, the backup Operator acts as Operator until the Operator announces their return in the game repository or a proposal names a new Operator.

**35.** While the backup Operator acts as Operator, the absent Operator's agreement is not required for a proposal to be adopted.

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

## Precedence

**29.** If two rules of the game conflict, an immutable rule prevails over a mutable one. Otherwise, a rule that explicitly claims precedence over the other prevails. Otherwise, or if each claims precedence over the other, the rule with the lower number prevails.

**30.** No rule may claim precedence over rule 29.

**31.** Rule 29 applies only to the rules of the game. It does not change how Ulex 1.1 resolves conflicts among its own provisions under rule 20.

**32.** When it is unclear how a rule applies, the Operator decides how to apply it until a proposal resolves the question. This does not limit a player's recourse to Ulex 1.1 under rule 20. A conflict or ambiguity found in the rules SHOULD be resolved by a proposal.

## Conventions

**25.** The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

**26.** Each rule has a permanent number, which is how it is cited (for example, "rule 13"). A rule's number says nothing about where it appears: rules MAY be moved between sections, and sections added, split or reordered, without changing any number.

**27.** A new rule takes the next number after the highest number ever assigned. An amended rule keeps its number.

**28.** A number is never reused. When a rule is repealed, it is removed from the ruleset and recorded, with its number and its last text, in [repealed.md](repealed.md).
