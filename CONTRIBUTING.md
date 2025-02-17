# Contributing to developer documentation site

Interested in contributing? That's awesome! Here are some guidelines to get started quickly and easily:

- [Reporting An Issue](#reporting-an-issue)
  - [Reporting A Documentation Issue](#reporting-a-documentation-issue)
  - [New Document Request](#new-document-request)
  - [Documentation Change Requests](#documentation-change-requests)
- [Working on Documentation](#working-on-documentation)
  - [Documentation Changes Branches](#documentation-changes-branches)
  - [Submitting Pull Requests](#submitting-pull-requests)
- [Conduct](#conduct)
- [Contributor License & Acknowledgments](#contributor-license--acknowledgments)
- [References](#references)

## Reporting An Issue

If you're about to raise an issue because you think you've found a problem with documentation, please read this first.

The GitHub issue tracker is the preferred channel for [Reporting a Documentation Issue](#reporting-a-documentation-issue), [New Documentation Feature Requests](#new-documentation-feature-requests), and [Submitting Pull Requests](#submitting-pull-requests), but please respect the following restrictions:

* Please **search for existing issues**. Help us keep duplicate issues to a minimum by checking to see if someone has already reported your problem or requested your idea.

* Please **be civil**. Keep the discussion on topic and respect the opinions of others. See also our [Contributor Code of Conduct](#conduct).

### Reporting a Documentation Issue

A documentation issue is a _demonstrable problem_ that is present in the documentation repository. Good reports are extremely helpful - thank you!

Guidelines for documentation issue reports:

1. **Use the GitHub issue search** &mdash; check if the issue has already been reported.

2. **Check if the issue has been fixed** &mdash; look for [closed issues in the
   current milestone](https://github.com/eosnetworkfoundation/docs/issues?q=is%3Aissue+is%3Aclosed) or try to find it using the latest `main` branch.

A good issue report shouldn't leave others needing to chase you up for more information. Be sure to include the details of your environment and relevant tests that demonstrate the problem.

[Report an issue](https://github.com/eosnetworkfoundation/docs/issues/new?title=%5Bdocs%5D%20Suggestion%20/%20Change%20Request)

### New Document Request

New document requests are welcome. Before you submit one be sure to have:

1. **Use the GitHub search** and check the new document hasn't already been requested.
2. Take a moment to think about whether your idea fits with the scope and aims of the project.
3. Remember, it's up to *you* to make a strong case to convince the project's leaders of the merits of this documentation request.

### Documentation Change Requests

If you have an idea for improvement to documentation, section, paragraph, section, etc - please be sure to:

1. **Use the GitHub search** and check someone else didn't get there first
2. Take a moment to think about the best way to make a case for, and explain what you're thinking. Are you sure this shouldn't really be
   [New Document Request](#new-document-request)?  Is it really one idea or is it many? What's the context? Why is what you are suggesting better than what's already there?

## Working on documentation

Documentation contributions are welcome and encouraged! If you are looking for a good place to start, check out the [good first issue](https://github.com/EOSIO/welcome/labels/good%20first%20issue) label in GitHub issues.

Also, please follow these guidelines when submitting your proposed documentation changes:

### Documentation Changes Branches

To get it out of the way:
- **[main](https://github.com/eosnetworkfoundation/docs/tree/main)** is the development branch. All work on the next release happens here so you should generally branch off `main`. Do **NOT** use this branch for a production site.
- **release/** branches, if any, contain stable releases of Docs. Some of these branches may be obsolete, a prerelease (release candidate), or designated as stable and ready for use in production. Generally do **NOT** use these branches to work on Docs' source unless you are working on a defect or change that would apply to a current stable release or release candidate. If in doubt, branch off of `main` and a Docs maintainer will chime in if you should switch to a release branch.

### Submitting Pull Requests

Pull requests are awesome. If you're looking to raise a PR for something which doesn't have an open issue, please think carefully about [raising an issue](#reporting-an-issue) which your PR can close. This makes it more likely that there will be enough information available for your PR to be properly tested and merged.

## Conduct

While contributing, please be respectful and constructive, so that participation in our project is a positive experience for everyone.

Examples of behavior that contributes to creating a positive environment include:
- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behavior include:
- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting/derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others’ private information, such as a physical or electronic address, without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

## Contributor License & Acknowledgments

Whenever you make a contribution to this project, you license your contribution under the same terms as set out in [LICENSE](./LICENSE), and you represent and warrant that you have the right to license your contribution under those terms.  Whenever you make a contribution to this project, you also certify in the terms of the Developer’s Certificate of Origin set out below:

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
1 Letterman Drive
Suite D4700
San Francisco, CA, 94129

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

## References

* Overall CONTRIB adapted from https://github.com/mathjax/MathJax/blob/master/CONTRIBUTING.md
* Conduct section adapted from the Contributor Covenant, version 1.4, available at https://www.contributor-covenant.org/version/1/4/code-of-conduct.html
