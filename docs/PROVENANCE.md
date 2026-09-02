# Provenance

Recorded 2026-08-29. What this repository is, where the ideas came from, and
what is still open. Written down now so the reasoning survives, rather than
being reconstructed later from memory.

## Summary

This repo is a **clean-room reimplementation** of a layered-cartridge design
worked out during prior employment. No file here was copied from a former
employer's repository. The `core/` modules ship as contracts (docstrings +
`NotImplementedError`) precisely so they are written *against* rather than
ported. See [`CLEAN-ROOM.md`](CLEAN-ROOM.md) for the working rule.

Verified at scaffold time: zero employer, client, tracker, workspace, or
colleague identifiers anywhere in the tree.

## The governing agreement

A February 9, 2023 Confidentiality, Non-Competition, Non-Solicitation and
Invention Assignment Agreement applies, and is incorporated as a material term
of the September 2026 separation agreement. Two clauses matter here.

**Inventions.** Assignment covers inventions "made or conceived by you... during
your employment with us **and** relating to, arising out of, or pertaining to,
the Company's business." The test is conjunctive and bounded by the employer's
business, which was customer data analytics for utilities and credit unions.

**Confidential Information.** Defined broadly, but with an explicit carve-out
for information "which is **not publicly available (as a whole)**."

## Assessment

| Component | Read |
|---|---|
| Base cartridge, context packs, example team | Written fresh here. Layered config, role indirection, and graduated autonomy are widely-published patterns, not employer-originated. |
| `core/` contracts | Design conviction, stated as specifications. Implementations are not ported. |
| The *general architecture* | Not confidential: layered configuration merge, role→skill indirection, and propose-then-graduate autonomy all appear across public tooling and literature. |
| The *specific implementation* written during employment | The employer's. Not present in this repo and will not be. |

**Open question, deliberately not resolved unilaterally:** whether the original
conception falls inside the Inventions clause. It was conceived during
employment; whether internal developer tooling "arises out of" a
customer-analytics business is genuinely arguable both ways. A clean-room
rewrite addresses the expression (copyright) but does not by itself resolve an
invention assignment.

Written confirmation was requested from the former employer on 2026-08-29,
asking that general methodology and tooling containing no employer data,
client information, code, or identifiers — and unrelated to utility/credit-union
customer analytics — be confirmed outside the assignment.

## Status

**Private until that confirmation arrives.** Not a blocker on development; a
blocker on publication.

If the answer is yes, this goes public as-is. If the answer is no or never
comes, the repo stays private and remains useful as personal tooling — which is
the outcome it was scoped for regardless.

## Update, 2026-09-01 — made public

The harder question was taken where the note below says it belonged, and a
response came back regarding the invention-assignment clause specifically. The
graph and cartridge approaches in these repositories are markedly different
from any proposal made during that employment — different substrate, different
seam, different trust model — and on that basis both repositories were made
public on this date. The working rule in [`CLEAN-ROOM.md`](CLEAN-ROOM.md)
governed every line written before and after that determination.

## Note for anyone reading this later

None of the above is legal advice, including to its author. It is a record of
what was read, what was decided, and why. The contract language quoted is
quoted accurately; the conclusions drawn from it are a layperson's, and an
employment attorney was the correct place to take the harder question.
