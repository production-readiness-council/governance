# System of Record Boundaries

## Principle

The website application is a read surface and structured workflow surface. GitHub is the public operating ledger for governance artifacts, proposals, review discussion, and versioned workflow documents.

## Track in GitHub

GitHub should hold:

- governance documents and amendments
- proposal intake records and triage discussion
- workflow templates and public checklists
- public review discussion where confidentiality is not required
- public publication-decision artifacts and version history
- contribution history relevant to role progression

## Track in application data

Application data should hold:

- structured report entities and report versions
- working-group membership and role assignments
- review assignments and reviewer-state metadata
- evidence item records and sandbox/test references
- audit logs for privileged actions
- publication state, re-review scheduling data, and internal workflow status fields

## Cross-linking rules

- Public application records should link back to canonical GitHub artifacts where applicable.
- GitHub records that affect published reports should link to the corresponding application record when one exists.
- A status visible in the application must not imply a governance state that lacks a corresponding required artifact.

## Boundary rules

- GitHub is the default public record for governance change.
- The application should not silently replace required public governance artifacts.
- Private or security-sensitive matters may use restricted channels, but the existence of the exception should be documented when appropriate.
