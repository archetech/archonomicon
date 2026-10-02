# Archonomicon
The [Archetech](https://archetech.com) Nomicon

**1.** The name of the [game](Nomicon/README.md) is Archonomicon.

**2.** The goal of the game is to decentralize the singularity.

**3.** All players must unanimously agree to all rule changes.

**4.** Proposals may add, amend or repeal a rule.

**5.** All rules should be logically self-consistent.

## Players

**6.** The players of the game are listed in [players.md](players.md).

**7.** A person becomes a player when a proposal adding them to the list is adopted.

**8.** A player may leave the game at any time by announcing it in the game repository, after which the Operator MUST remove them from the list.

## Proposals

**9.** The rules of the game are the text of the default branch of the [game repository](https://github.com/archetech/archonomicon).

**10.** A proposal is a pull request to the game repository that adds, amends or repeals rules.

**11.** Anyone MAY submit a proposal, but only the agreement of players counts toward its adoption.

**12.** The Operator is the player who maintains the game repository and carries out the provisions of the rules that are not yet automated. The Operator is [macterra](https://github.com/macterra).

**13.** A proposal is adopted when the Operator merges it. By merging a proposal, the Operator certifies that all players agreed to it.

**14.** A proposal MUST state the change and the reason for it. It SHOULD also state the alternatives considered and its effect on compatibility and security in the projects under jurisdiction.

**15.** A player agrees to a proposal by approving its pull request. A player who submits a proposal agrees to it by submitting it, and the Operator's merge counts as the Operator's agreement.

**16.** An agreement applies only to the text of the proposal as it was when the player approved it. If the proposal changes after that, the earlier agreement no longer counts.

**17.** The adopted text of a proposal is exactly the text merged. A proposal closed without merging is not adopted; it MAY be submitted again.

**18.** An adopted rule change takes effect when it is merged and does not apply to anything that happened before then.

**19.** Every change made to the game repository before this rule was adopted, including [Proposal #1](https://github.com/archetech/archonomicon/pull/1), is ratified as a validly adopted rule change.

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

**29.** If two rules of the game conflict, a rule that explicitly claims precedence over the other prevails. Otherwise, or if each claims precedence over the other, the rule with the lower number prevails.

**30.** A claim of precedence over rule 29 or over this rule has no effect, whatever rule 29 says.

**31.** Rule 29 applies only to the rules of the game. It does not change how Ulex 1.1 resolves conflicts among its own provisions under rule 20.

**32.** When it is unclear how a rule applies, the Operator decides how to apply it until a proposal resolves the question. This does not limit a player's recourse to Ulex 1.1 under rule 20. A conflict or ambiguity found in the rules SHOULD be resolved by a proposal.

## Conventions

**25.** The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in these rules are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).

**26.** Each rule has a permanent number, which is how it is cited (for example, "rule 13"). A rule's number says nothing about where it appears: rules MAY be moved between sections, and sections added, split or reordered, without changing any number.

**27.** A new rule takes the next number after the highest number ever assigned. An amended rule keeps its number.

**28.** A number is never reused. When a rule is repealed, it is removed from the ruleset and recorded, with its number and its last text, in [repealed.md](repealed.md).
