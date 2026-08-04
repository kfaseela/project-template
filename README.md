# CNCF Project Template Repository

This is a [template repository][template-repo] for CNCF projects created by [CNCF SIG Contributor
Strategy][contrib-strat]. You can use it to either start a new repository that
has all the required files for a CNCF project or just grab the particular files
that you need.

## Steps

1. Click **Use this template** and create a copy of this repository.

    ![Green button that says "Use this template"](https://user-images.githubusercontent.com/1368985/95903529-e9c32f00-0d5b-11eb-8723-4369f7c9e044.png)
1. Remove **.github/settings.yml**. This is not a template and contains
   configuration specific our repository. You should not keep this file.
1. Customize every [required template](#required-templates) and address each TODO item.

### Customize Templates

Each file is a template with instructions to customize the contents for your project.
Most files use comments with TODO to call out where you need to make changes. We recommend
viewing the files in raw or text form so that you can see the comments. 

For example in markdown files, we use `<!-- TODO: ... -->` to provide additional
guidance or indicate where action is required but you won't see those comments
when you view the markdown file in GitHub unless you view the raw text.

## Templates

### Required

These files are required for all CNCF projects. The TOC checks for these during due diligence.

* [LICENSE](LICENSE) - Apache 2.0 or CNCF-approved license
* [README-template.md](README-template.md) - Project README (rename to README.md)
* [CONTRIBUTING.md](CONTRIBUTING.md) - How to contribute
* [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) - CNCF Code of Conduct
* [MAINTAINERS.md](MAINTAINERS.md) - Current maintainers with affiliations
* [GOVERNANCE.md](GOVERNANCE.md) - Choose a governance model:
  * [GOVERNANCE-maintainer.md](GOVERNANCE-maintainer.md) - Maintainer council
  * [GOVERNANCE-elections.md](GOVERNANCE-elections.md) - Elected steering committee
  * [GOVERNANCE-subprojects.md](GOVERNANCE-subprojects.md) - Federated subprojects
* [SECURITY.md](SECURITY.md) - Vulnerability reporting process

### Recommended

These files are recommended and become increasingly important at incubation and graduation.

* [ADOPTERS.md](ADOPTERS.md) - Production adopters list (required for moving levels)
* [CONTRIBUTOR_LADDER.md](CONTRIBUTOR_LADDER.md) - Contributor roles and progression
* [RELEASES.md](RELEASES.md) - Release process (required at incubation, detailed at graduation)
* [REVIEWING.md](REVIEWING.md) - Code review guidelines
* [DESIGN-PROPOSALS.md](DESIGN-PROPOSALS.md) - Design proposal process
* [CODEOWNERS](CODEOWNERS) - Code ownership mapping (should match GOVERNANCE.md)
* [.github/ISSUE_TEMPLATE/](.github/ISSUE_TEMPLATE/) - Bug report and feature request templates
* [.github/PULL_REQUEST_TEMPLATE.md](.github/PULL_REQUEST_TEMPLATE.md) - PR checklist

[template-repo]: https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[contrib-strat]: https://github.com/cncf/sig-contributor-strategy/blob/master/README.md

Note: This is the README file for the templates repo. Please use [README-template.md](README-template.md)
as a template for your project README.
