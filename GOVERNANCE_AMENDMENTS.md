# Governance Amendment Process

## Purpose

This process defines how governance artifacts are changed so that authority boundaries and workflow rules remain public, reviewable, and traceable.

## When an amendment is required

Use this process when changing:

- role authority boundaries
- publication authority or review authority
- report lifecycle gates
- sponsor non-interference rules
- role criteria or promotion rules
- GitHub versus application system-of-record boundaries

## Amendment workflow

1. Open a governance change issue in the `.github` repository using the governance change template.
2. Identify the current rule and the exact proposed change.
3. Link the affected governance artifact in this repository.
4. Record rationale and expected workflow impact.
5. Obtain review from the relevant maintainers or governance participants.
6. Merge the document change through a pull request.
7. Record the adopted change in `DECISIONS.md` if the amendment materially changes operating rules.

## Approval rule

Changes that affect publication authority, role authority, or sponsor constraints should be treated as Technical Council-level decisions unless a narrower delegation is later documented.

## Draft and final state

A proposed amendment is not effective until the governing document is updated on the default branch through the documented review path.

## Emergency exception

Urgent corrections may be merged quickly to fix broken references, dangerous ambiguity, or operational inconsistency, but the rationale should still be documented in the pull request and decision log.
