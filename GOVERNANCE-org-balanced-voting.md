# Org-Balanced Voting

This module can be adopted by any CNCF project governance model to prevent organizational concentration of governance decisions. It is designed to be added to an existing governance document, not used standalone.

<!-- template begins here -->

## Org-Balanced Voting for [TODO: PROJECTNAME]

To ensure that governance decisions reflect the interests of the broader community and not just the largest contributing organization, [TODO: PROJECTNAME] uses org-balanced voting for the following decision types:

- [TODO: List applicable decision types, e.g. governance changes, steering elections, strategic direction, roadmap priorities]

### How It Works

Each organization (employer) gets [TODO: one / up to two] vote(s) on org-balanced decisions, regardless of how many maintainers that organization employs. Independent contributors each receive one vote.

**Determining organization:** A maintainer's organization is their current employer as listed in [MAINTAINERS.md](./MAINTAINERS.md). Independent contractors or self-employed contributors are each treated as their own organization. If a maintainer's affiliation is unclear, the [TODO: Maintainer Council / Steering Committee] will determine it.

### Examples

**Example 1 - Simple majority with org balance:**
The project has 6 maintainers: 3 from Company A, 2 from Company B, and 1 independent. A governance change requires a simple majority of organizational votes. There are 3 organizational votes possible (Company A, Company B, Independent). Company A's 3 maintainers collectively cast 1 vote. The change passes with 2 of 3 organizational votes.

**Example 2 - Steering election with org balance:**
The project elects a 5-seat steering committee. No more than [TODO: 1 / 2] seat(s) may be held by employees of the same organization. If election results would exceed this limit, the lowest vote-getter from the over-represented organization is replaced by the next-highest vote-getter from a different organization.

### Scope

Org-balanced voting applies to governance decisions listed above. Day-to-day technical decisions (PR review, merge, release) continue to follow the project's standard decision-making process (typically lazy consensus among maintainers).

### Adoption

To adopt this module, add the applicable sections to your project's governance document and list the specific decision types that use org-balanced voting. Update your MAINTAINERS.md to ensure all affiliations are current.

<!-- For Maintainer Council projects, add this to your Voting section. -->
<!-- For Steering Committee projects, add this to your Limitations on Company Representation section. -->
<!-- For Federated Subproject projects, add this to your Steering Committee Elections section. -->
