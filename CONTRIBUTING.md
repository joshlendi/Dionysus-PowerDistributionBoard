# Contributing
The following is a set of guidelines for contributing. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[FAQ](#frequently-asked-questions)
  * [Common Questions](#common-questions)

[Before Getting Started?](#before-getting-started)
  * [Design Decisions](#design-decisions)

[How to Contribute?](#how-to-contribute)
  * [Reporting a Bug](#reporting-a-bug)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Pull Requests](#pull-requests)

[Styleguides and Standards](#styleguides-and-standards)
  * [Styleguide 1](#styleguide-1)
  * [Styleguide](#styleguide-2)
  * [Standard 1](#standard-1)
  * [Standard 2](#standard-2)
  * [Documentation](#documentation)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct
In the interest of fostering an open and welcoming environment, we as contributors and maintainers pledge to making participation in our project and our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

## Frequently Asked Questions
First check the [FAQ](URL) in the [Wiki](URL) to see if your question has already been answered.
### Common Questions

## Before Getting Started
### Design Decisions
When we make a significant decision in how we maintain the project and what we can or cannot support, we will document it in the [atom/design-decisions repository](https://github.com/atom/design-decisions). If you have a question around how we do things, check to see if it is documented there. If it is *not* documented there, please open a new topic on [Discuss, the official Atom message board](https://discuss.atom.io) and ask your question.

## How to Contribute
### Reporting a bug
This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report).

<!--Fill out [the required template](https://github.com/atom/.github/blob/master/.github/ISSUE_TEMPLATE/bug_report.md), the information it asks for helps us resolve issues faster.-->

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Before Submitting a Bug Report
* Double check your issue. You might be able to find the cause of the problem and fix things yourself. Most importantly, check if you can reproduce the problem if the problem happens when you run Atom in, and if you can get the desired behavior by changing.
* **Check the [FAQs](URL)** for a list of common questions and problems.
* **Determine which repository the problem should be reported in**.
* **Perform a cursory search** to see if the problem has already been reported. If it has **and the issue is still open**, add a comment to the existing issue instead of opening a new one.

### Submitting a Good Bug Report
Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). Create an issue on that repository.

<!--provide the following information by filling in [the template](URL)-->

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started Atom, e.g. which command exactly you used in the terminal, or how you started Atom otherwise. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you moved the cursor to the end of a line, explain if you used the mouse, or a keyboard shortcut or an Atom command, and if so which one?
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with the [Keybinding Resolver](https://github.com/atom/keybinding-resolver) shown**. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Can you reproduce the problem?**
* **Did the problem start happening recently** (e.g. after updating to a new version) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version?** What's the most recent version in which the problem doesn't happen? You can download older versions from older repository branches.
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.
* If the problem is related to working with files (e.g. opening and editing files), **does the problem happen for all files and projects or only some?** Does the problem happen only when working with local or remote files (e.g. on network drives), with files of a specific type (e.g. only JavaScript or Python files), with large files or files with very long lines, or with files in a specific encoding? Is there anything else special about the files you are using?

Include details about your configuration and environment:

* **Which version are you using?**
* **What's the name and version of the OS you're using**?
* **Are you running it on a virtual machine?** If so, which VM software are you using and which operating systems and versions are used for the host and the guest?
* **Which keyboard layout are you using?** Are you using a US layout or some other layout?

### Suggesting Enhancements
* Feel free to [create a new issue](URL) to document the feature you are planning to add. This will allow others to see and comment on what you would plan to add to the library.

### Pull Requests

## Styleguides and Standards
### Styleguide 1
### Styleguide 2
### Standard 1
### Standard 2
### Documentation

## Additional Notes
### Issue and Pull Request Labels
This section lists the labels we use to help us track and manage issues and pull requests.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. To help you find issues and pull requests, each label is listed with search links for finding open items with that label in `atom/atom` only and also across all Atom repositories. We  encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

#### Type of Issue and Issue State

| Label name |  Description |
| --- | --- | 
| `enhancement` | Feature requests. |
| `bug` | Confirmed bugs or reports that are very likely to be bugs. |
| `question` | Questions more than bug reports or feature requests (e.g. how do I do X). |
| `feedback` |  General feedback more than bug reports or feature requests. |
| `help-wanted` | The Atom core team would appreciate help from the community in resolving these issues. |
| `beginner` |  Less complex issues which would be good first issues to work on for users who want to contribute to Atom. |
| `more-information-needed` | More information needs to be collected about these problems or feature requests (e.g. steps to reproduce). |
| `needs-reproduction` | Likely bugs, but haven't been reliably reproduced. |
| `blocked` | Issues blocked on other issues. |
| `duplicate` | Issues which are duplicates of other issues, i.e. they have been reported before. |
| `wontfix` | The Atom core team has decided not to fix these issues for now, either because they're working as intended or for some other reason. |
| `invalid` | Issues which aren't valid (e.g. user errors). |
| `package-idea` | Feature request which might be good candidates for new packages, instead of extending Atom or core Atom packages. |

#### Topic Categories

| Label name | Description |
| --- | --- |
| `windows` | Related to Atom running on Windows. |
| `linux` | Related to Atom running on Linux. |
| `mac` | Related to Atom running on macOS. |
| `documentation` | Related to any type of documentation (e.g. [API documentation](https://atom.io/docs/api/latest/) and the [flight manual](https://flight-manual.atom.io/)). |
| `performance` | Related to performance. |
| `security` | Related to security. |
| `ui` | Related to visual design. |
| `api` | Related to Atom's public APIs. |
| `uncaught-exception` | Issues about uncaught exceptions, normally created from the [Notifications package](https://github.com/atom/notifications). |
| `crash` | Reports of Atom completely crashing. |
| `auto-indent` | Related to auto-indenting text. |
| `encoding` | Related to character encoding. |
| `network` | Related to network problems or working with remote files (e.g. on network drives). |
| `git` | Related to Git functionality (e.g. problems with gitignore files or with showing the correct file status). |

#### Pull Request Labels

| Label name |  Description
| --- | --- |
| `work-in-progress` | Pull requests which are still being worked on, more changes will follow. |
| `needs-review` | Pull requests which need code review, and approval from maintainers or Atom core team. |
| `under-review` | Pull requests being reviewed by maintainers or Atom core team. |
| `requires-changes` | Pull requests which need to be updated based on review comments and then reviewed again. |
| `needs-testing` |  Pull requests which need manual testing. |
