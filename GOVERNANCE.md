# Project Governance

Because project governance varies widely, we offer several templates covering
common systems of governance used by various CNCF projects.  In order to
adopt them, choose the one closest to how you want your project to be governed,
then rename the appropriate `GOVERNANCE-xxx.md` file to GOVERNANCE.md,
overwriting this file, and customize it.  

See the Contributor Strategy document on [Leadership Selection](https://contribute.cncf.io/maintainers/governance/leadership-selection/)
for more background.  Please also review [SustainOSS's Governance Readiness Checklist](https://sustainers.github.io/governance-readiness/)
as preparation for making governance decisions.

## Governance Templates Supplied

`GOVERNANCE-maintainer.md` supplies rules for a simple self-selecting council
of Maintainers as project governance.  It assumes that there is no distinction
between the contributors who create the majority of code and documentation for
the project and the group who makes all decisions for the project.  This
governance is suitable for small, very unified projects, and is often a good
starting point for project governance.  It is based on the Jaeger project's
governance.

`GOVERNANCE-elections.md` is a template for an elected steering committee,
where senior leadership is elected by the body of contributors.  This is a
suitable structure for larger projects with an established community.  The
template is based on Kubernetes project governance.

`GOVERNANCE-subprojects.md` is a template for a "project of projects" where
the CNCF project is more of an umbrella for a bunch of closely related
subprojects.  It is based on Konveyor project governance.

## Choosing a Governance Model by Maturity

Projects at different CNCF maturity levels have different governance expectations. The TOC evaluates governance as part of the due diligence process for moving levels.

* **Sandbox:** `GOVERNANCE-maintainer.md` is appropriate. The focus is on
  having documented governance at all, with clear maintainer roles and a
  code of conduct.

* **Incubation:** `GOVERNANCE-maintainer.md` or `GOVERNANCE-elections.md`,
  depending on community size. Projects should demonstrate that governance
  is actively used (not just documented), including evidence of maintainer
  additions or replacements, and that decision-making processes have been
  exercised.

* **Graduation:** Governance must demonstrate organizational diversity in
  leadership. The TOC expects to see maintainers from at least 2
  organizations, org-balanced voting or representation limits, and a
  documented maintainer lifecycle including emeritus status. The project
  must survive the withdrawal of any single organization.

## Common Governance Anti-Patterns

The following patterns have been identified across CNCF project reviews as governance weaknesses that delay or block level transitions:

* **Cosmetic diversity:** Titles or roles are distributed across
  organizations, but decision-making authority remains concentrated in a
  single organization.

* **Documented-but-never-used governance:** A GOVERNANCE.md exists but has
  never been exercised. No evidence of elections held, maintainers added
  or removed, or votes taken.

* **Governance/code divergence:** CODEOWNERS, branch protection rules, or
  repository permissions do not match the roles described in governance
  documents.

* **Practice period shortcuts:** Projects adopt complex governance
  structures (e.g., elected steering committee) immediately before
  applying to move levels, without demonstrating a period of active use.
