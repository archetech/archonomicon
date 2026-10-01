# Archonomicon
The [Archetech](https://archetech.com) Nomicon

**101.** The name of the [game](Nomicon/README.md) is Archonomicon.

**102.** The goal of the game is to decentralize the singularity.

**103.** All players must unanimously agree to all rule changes.

**104.** Proposals may add, amend or repeal a rule.

**105.** All rules should be logically self-consistent.

## Players

**201.** The players of the game are listed in [players.md](players.md).

**202.** A person becomes a player when a proposal adding them to the list is adopted.

**203.** A player may leave the game at any time by announcing it in the game repository, after which the Operator MUST remove them from the list.

## Proposals

**301.** The rules of the game are the text of the default branch of the [game repository](https://github.com/archetech/archonomicon).

**302.** A proposal is a pull request to the game repository that adds, amends or repeals rules.

**303.** Anyone MAY submit a proposal, but only the agreement of players counts toward its adoption.

**304.** The Operator is the player who maintains the game repository and carries out the provisions of the rules that are not yet automated. The Operator is [macterra](https://github.com/macterra).

**305.** A proposal is adopted when the Operator merges it. By merging a proposal, the Operator certifies that all players agreed to it.

**306.** A proposal MUST state the change and the reason for it. It SHOULD also state the alternatives considered and its effect on compatibility and security in the projects under jurisdiction.

**307.** A player agrees to a proposal by approving its pull request. A player who submits a proposal agrees to it by submitting it, and the Operator's merge counts as the Operator's agreement.

**308.** An agreement applies only to the text of the proposal as it was when the player approved it. If the proposal changes after that, the earlier agreement no longer counts.

**309.** The adopted text of a proposal is exactly the text merged. A proposal closed without merging is not adopted; it MAY be submitted again.

**310.** An adopted rule change takes effect when it is merged and does not apply to anything that happened before then.

**311.** Every change made to the game repository before this rule was adopted, including [Proposal #1](https://github.com/archetech/archonomicon/pull/1), is ratified as a validly adopted rule change.

## Jurisdiction

**401.** Only [Ulex 1.1](https://github.com/proftomwbell/Ulex/tree/master/versions/1.1) governs any claim or question arising under or related to this agreement, including the proper forum for resolving disputes, all rules applied therein, and the form and effect of any judgement.

**402.** Projects that fall under the jurisdiction of Archonomicon:

* [Archon](https://github.com/archetech/archon)
* [Archon schemas](https://github.com/archetech/schemas)
* [Sigil](https://github.com/archetech/sigil)
* [did:cid specifications](https://github.com/archetech/didcid-specs)

**403.** A project is added to or removed from the list in rule 402 only by an adopted proposal.

**404.** Changes to a project's repository are not rule changes. They are made through the project's own development process, and they MUST comply with the rules of the game.

**405.** A project MAY keep its own rules in its repository, such as contribution guidelines or instructions for coding agents. Project rules MUST NOT conflict with the rules of the game, and where they do, the rules of the game prevail.

## Conventions

**501.** The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

**502.** Each rule has a permanent number, which is how it is cited (for example, "rule 305"). The hundreds identify the rule's section, and a new section takes the next unused hundred.

**503.** A new rule takes the next unused number in its section. An amended rule keeps its number.

**504.** A number is never reused. When a rule is repealed, its number stays in the ruleset with the word "Repealed" in place of its text.
