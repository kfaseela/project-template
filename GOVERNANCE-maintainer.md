# [TODO:PROJECTNAME] Project Governance

[Instructions](https://contribute.cncf.io/maintainers/github/templates/required/governance-maintainer/)

<!-- template begins here-->

The [TODO:PROJECTNAME]  project is dedicated to creating [TODO:Goals of project].  
This governance explains how the project is run.

- [Values](#values)
- [Maintainers](#maintainers)
- [Becoming a Maintainer](#becoming-a-maintainer)
- [Meetings](#meetings)
- [CNCF Resources](#cncf-resources)
- [Code of Conduct Enforcement](#code-of-conduct)
- [Security Response Team](#security-response-team)
- [Voting](#voting)
- [Modifications](#modifying-this-charter)

## Values

The [TODO: PROJECTNAME] and its leadership embrace the following values:

* Openness: Communication and decision-making happens in the open and is discoverable for future
  reference. As much as possible, all discussions and work take place in public
  forums and open repositories.

* Fairness: All stakeholders have the opportunity to provide feedback and submit
  contributions, which will be considered on their merits.

* Community over Product or Company: Sustaining and growing our community takes
  priority over shipping code or sponsors' organizational goals.  Each
  contributor participates in the project as an individual.

* Vendor Neutrality: The project direction and decisions are not controlled by
  any single organization. Maintainer selection, roadmap prioritization, and
  release decisions are made based on project merit, not employer affiliation.

* Inclusivity: We innovate through different perspectives and skill sets, which
  can only be accomplished in a welcoming and respectful environment.

* Participation: Responsibilities within the project are earned through
  participation, and there is a clear path up the contributor ladder into leadership
  positions.

## Maintainers

[TODO: PROJECTNAME] Maintainers have write access to the [project GitHub repository](TODO).
They can merge their own patches or patches from others. The current maintainers
can be found in [MAINTAINERS.md](./MAINTAINERS.md).  Maintainers collectively manage the project's
resources and contributors.

This privilege is granted with some expectation of responsibility: maintainers
are people who care about the [TODO: PROJECTNAME] project and want to help it grow and
improve. A maintainer is not just someone who can make changes, but someone who
has demonstrated their ability to collaborate with the team, get the most
knowledgeable people to review code and docs, contribute high-quality code, and
follow through to fix issues (in code or tests).

A maintainer is a contributor to the project's success and a citizen helping
the project succeed.

The collective team of all Maintainers is known as the Maintainer Council, which
is the governing body for the project.

### Becoming a Maintainer

To become a Maintainer you need to demonstrate the following:

  * commitment to the project:
    * participate in discussions, contributions, code and documentation reviews
      for [TODO: Time Period] or more,
    * perform reviews for [TODO:Number] non-trivial pull requests,
    * contribute [TODO:Number] non-trivial pull requests and have them merged,
  * ability to write quality code and/or documentation,
  * ability to collaborate with the team,
  * understanding of how the team works (policies, processes for testing and code review, etc),
  * understanding of the project's code base and coding and documentation style.
  <!-- add any additional Maintainer requirements here -->

A new Maintainer must be proposed by an existing maintainer by sending a message to the
[developer mailing list](TODO: List Link). A simple majority vote of existing Maintainers
approves the application.  Maintainer nominations will be evaluated without prejudice
to employer or demographics and should consider the organizational diversity of the
maintainer group.

<!-- For projects approaching graduation, consider adding: -->
<!-- The maintainers will avoid nominating new maintainers from any organization -->
<!-- that already employs 50% or more of existing maintainers. -->

Maintainers who are selected will be granted the necessary GitHub rights,
and invited to the [private maintainer mailing list](TODO).

### Removing a Maintainer

Maintainers may resign at any time if they feel that they will not be able to
continue fulfilling their project duties.

Maintainers may also be removed after being inactive, failure to fulfill their 
Maintainer responsibilities, violating the Code of Conduct, or other reasons.
Inactivity is defined as a period of very low or no activity in the project 
for [TODO: Number, e.g. 6-12] months or more, with no definite schedule to return 
to full Maintainer activity.

A Maintainer may be removed at any time by a 2/3 vote of the remaining maintainers.

### Emeritus Maintainers

Depending on the reason for removal or resignation, a Maintainer may be converted 
to Emeritus status. Emeritus Maintainers are recognized for their past contributions 
and may still be consulted on project matters, but do not have voting rights or 
merge access. Emeritus Maintainers are listed in [MAINTAINERS.md](./MAINTAINERS.md) 
under a separate Emeritus section.

An Emeritus Maintainer may be reinstated to active Maintainer status by a simple 
majority vote of existing Maintainers, provided they meet the current Maintainer 
requirements and can commit to ongoing participation.

## Meetings

Time zones permitting, Maintainers are expected to participate in the public
developer meeting, which occurs
[TODO: Details of regular developer or maintainer meeting here].  

Maintainers will also have closed meetings in order to discuss security reports
or Code of Conduct violations.  Such meetings should be scheduled by any
Maintainer on receipt of a security issue or CoC report.  All current Maintainers
must be invited to such closed meetings, except for any Maintainer who is
accused of a CoC violation.

## CNCF Resources

Any Maintainer may suggest a request for CNCF resources, either in the
[mailing list](TODO: link to developer/maintainer mailing list), or during a
meeting.  A simple majority of Maintainers approves the request.  The Maintainers
may also choose to delegate working with the CNCF to non-Maintainer community
members, who will then be added to the [CNCF's Maintainer List](https://github.com/cncf/foundation/blob/main/project-maintainers.csv)
for that purpose.

## Code of Conduct

[Code of Conduct](./code-of-conduct.md)
violations by community members will be discussed and resolved
on the [private Maintainer mailing list](TODO).  If a Maintainer is directly involved
in the report, the Maintainers will instead designate two Maintainers to work
with the CNCF Code of Conduct Committee in resolving it.

## Security Response Team

The Maintainers will appoint a Security Response Team to handle security reports.
This committee may simply consist of the Maintainer Council themselves.  If this
responsibility is delegated, the Maintainers will appoint a team of at least two 
contributors to handle it.  The Maintainers will review who is assigned to this
at least once a year.

The Security Response Team is responsible for handling all reports of security
holes and breaches according to the [security policy](SECURITY.md).

## Voting

While most business in [TODO: PROJECTNAME] is conducted by "[lazy consensus](https://community.apache.org/committers/lazyConsensus.html)", 
periodically the Maintainers may need to vote on specific actions or changes.
A vote can be taken on [the developer mailing list](TODO) or
[the private Maintainer mailing list](TODO) for security or conduct matters.  
Votes may also be taken at [the developer meeting](TODO).  Any Maintainer may
demand a vote be taken.

Most votes require a simple majority of all Maintainers to succeed, except where
otherwise noted.  Two-thirds majority votes mean at least two-thirds of all 
existing maintainers.

<!-- For projects with maintainers from multiple organizations, consider adding -->
<!-- an org-balanced voting clause. Projects with org-balanced governance      -->
<!-- demonstrate stronger health indicators for CNCF level transitions.       -->
<!-- Example: "No single organization's employees may cast more than 1/3 of   -->
<!-- the total votes on any decision." -->

## When to Evolve This Governance

The Maintainer Council model works well for focused projects with a small, cohesive group of contributors. As the project grows, watch for these signals that a governance transition may be needed:

* **Decisions stall.** When the maintainer group is too large for lazy consensus to work, or when decisions affect subgroups differently, a delegation structure (working groups, SIGs) helps.
* **New contributors cannot find a path in.** If the only path to influence is "become a maintainer," the project needs intermediate roles (reviewer, approver). Projects with intermediate roles produce more diverse maintainer pools because they give external contributors a visible progression path.
* **A single organization dominates.** When one company holds a majority of maintainer seats, consider adding [org-balanced voting](governance/ORG-BALANCED-VOTING.md), company representation caps, or transitioning to an [elected steering committee](GOVERNANCE-elections.md).
* **Subprojects diverge.** When parts of the project develop their own contributor communities or release cadences, consider [federated subproject governance](GOVERNANCE-subprojects.md).

These transitions are a sign of project growth, not governance failure.

## Modifying this Charter

Changes to this Governance and its supporting documents may be approved by 
a 2/3 vote of the Maintainers.
