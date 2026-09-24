# PP-SPEC-026: Proof-Derived Value and the Speculative Token Fallacy

**Status:** Draft (internal)
**Author:** Craig Ellrod
**Date:** Sept 18, 2026
**License:** CC BY-ND 4.0
**Related:** PP-SPEC-023 (Structural Independence and the Fidelity-at-Capture Requirement), PP-SPEC-024 (The Self-Attestation Oxymoron)

## Cite as

Ellrod, C. (2026). PP-SPEC-026: Proof-Derived Value and the Speculative Token Fallacy.
Proof Economy Standards Alliance (PESA). https://doi.org/10.5281/zenodo.22821518

## Summary

Every existing digital currency derives value from scarcity of computation, scarcity of capital commitment, or scarcity of belief. None derive value from empirically measured performance of a real-world claim. This spec defines what a genuinely proof-derived value system requires structurally, and why systems that skip these requirements are speculative tokens wearing proof-economy language.

## The Distinction

A value unit is proof-derived only if three conditions hold simultaneously:

1. **Issuance is gated by an independently verified event**, not by computation, staking, or governance vote. The event must satisfy structural independence as defined in PP-SPEC-023 — issuance triggered by a self-attested claim is not proof-derived, regardless of what cryptographic wrapper surrounds it.
2. **The measured claim is falsifiable and specific**, not a general reputation score or sentiment signal. "This product detected this attack under these conditions" is falsifiable. "This entity is trustworthy" is not.
3. **Issuance authority is separable from the party whose performance is being measured.** The entity that benefits from a favorable measurement cannot be the entity that mints the value unit representing that measurement. This is the Self-Attestation Oxymoron (PP-SPEC-024) applied to issuance rather than to reporting.

Any system failing condition 3 is self-attested value creation. It will inherit every failure mode of self-attested proof, with the added defect that the incentive to misreport now has a direct financial payoff rather than a reputational one — which makes the incentive worse, not neutral.

## Why This Is Not "Proof Protocol Is a Blockchain"

Proof Protocol's infrastructure — anchoring, witnessing, sealing — has no token, wallet, or chain, and nothing in this spec changes that. This spec defines a property a value system must have to legitimately claim the word "proof" in its name. It does not commit Proof Protocol to issuing, operating, or endorsing any such system. A category can be defined without an instance of that category being built or launched by the party defining it. This spec draws the boundary; it does not cross it.

## The Adjacent Failure: Speculative Proof-Washing

As proof infrastructure becomes a recognized category, expect token projects to describe themselves as "proof-backed" or "efficacy-derived" while satisfying none of the three conditions above — typically by using proof language to describe a governance vote, a staking mechanism, or a self-reported metric. This is proof-washing: borrowing the credibility of independently verified evidence to describe a value system that has no independent verification anywhere in its issuance path. The test in this spec is the filter. Apply the three conditions before accepting the label.

## Relation to Existing Value Systems

Proof-of-work ties issuance to computational expenditure, which is real but unrelated to any claim about the world. Proof-of-stake ties issuance to capital commitment, which measures willingness to bear risk, not accuracy of a claim. Neither satisfies condition 2: neither issuance mechanism corresponds to a falsifiable claim about real-world performance. This is not a criticism of either system's design goals — they were not built to solve this problem. It is a statement that neither can be retrofitted into a "proof-derived" claim without breaking the definition this spec sets out.

## Scope

This spec defines a category and a three-part test. It does not disclose, describe, or claim any specific mechanism for issuance, minting, consensus, or token economics. Any such mechanism, if and when disclosed, will be the subject of a separate specification.

## Provenance

This document is timestamped and anchored via Zenodo, DOI https://doi.org/10.5281/zenodo.22821518, as of the publication date above, establishing public priority for the proof-derived value category definition independent of and prior to any adoption by third-party projects.
