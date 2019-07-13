# Contributing to the Cotton Project

# WIP

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Cotton Project mods, which are hosted in the [Cotton Project Organization](https://github.com/CottonMC) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[I don't want to read this whole thing, I just have a question!!!](#i-dont-want-to-read-this-whole-thing-i-just-have-a-question)

[How Can I Contribute?](#how-can-i-contribute)
  * [Reporting Bugs](#reporting-bugs)
  * [Suggesting Enhancements](#suggesting-enhancements)
  * [Your First Code Contribution](#your-first-code-contribution)
  * [Pull Requests](#pull-requests)

[Additional Notes](#additional-notes)
  * [Issue and Pull Request Labels](#issue-and-pull-request-labels)

## Code of Conduct

This project and everyone participating in it is governed by the [Cotton Project Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to any active member of the project.

## I don't want to read this whole thing I just have a question!!!

Please don't file an issue to ask a question. You'll get faster results by using our [Discord Server](https://discord.gg/rNgYs3Z).

## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for the Cotton Project. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :computer: :computer:, and find related reports :mag_right:.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out the required template, the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your bug is related to, create an issue on that repository and provide the following information by filling in the template.

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you used the processing recipe, explain if you used your personal implementation, or the library’s one, etc.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, list the typed combinations and the time codes. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **If you're reporting that Minecraft crashed**, include a crash report with a stack trace from the operating system. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), or put it in a [Gist](https://gist.github.com/) and provide link to that gist.
* **If the problem is related to performance or memory**, include a CPU profile capture with your stack trace.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Can you reproduce the problem in other conditions**, e.g. using other versions or other set of mods?
* **Did the problem start happening recently** (e.g. after updating to a new version of the mod or its dependency) or was this always a problem?
* If the problem started happening recently, **can you reproduce the problem in an older version of the mod?** What's the most recent version in which the problem doesn't happen?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **Which version of the mod and its dependencies are you using?** You can get the exact version by using ModMenu, MultiMC launcher or by opening the mod JAR, finding `fabric.mod.json` in there, opening it and finding `version` field.
* **Which other mods do you have installed?** You can get that list by using ModMenu, MultiMC launcher or by retrieving used mods through `fabric.mod.json` files inside JARs and nested JARs.
* **Are you using local configuration files?** Those files are usually in your Minecraft instance's `config` folder or a subfolder.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for a Cotton project, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](ISSUE_TEMPLATE.md), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Check if you're using the latest version of the mod.** Your suggestion might already have been included in an update.
* **Perform a [cursory search](https://github.com/search?q=+is%3Aissue+user%3ACottonMC)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which project your enhancement suggestion is related to, create an issue on its repository and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of the mod which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
* **Specify which version of the mod you're using.** You can get the exact version from the mod menu or the mod JAR's file name.

### Your First Code Contribution

Unsure where to begin contributing to Cotton? You can start by looking through these `good first issue` and `help wanted` issues:

* [Good first issues][good-first-issue] - issues which should only require a few lines of code, and a test or two.
* [Help wanted issues][help-wanted] - issues which should be a bit more involved than `beginner` issues.

Both issue lists are sorted by total number of comments. While not perfect, number of comments is a reasonable proxy for impact a given change will have.

### Pull Requests

The process described here has several goals:

- Maintain the Cotton project's quality
- Fix problems that are important to users
- Engage the community in working toward the best possible mods
- Enable a sustainable system for Cotton's maintainers to review contributions

Please follow these steps to have your contribution considered by the maintainers:

1. Follow all instructions in [the template](PULL_REQUEST_TEMPLATE.md)
2. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

## Additional Notes

### Issue and Pull Request Labels

This section lists the labels we use to help us track and manage issues and pull requests. Most labels are used across all Cotton
repositories, but some might be specific to a single repository.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. For example, you might be interested in [open issues across `CottonMC/Cotton` and all Cotton-owned packages which are labeled as bugs](https://github.com/search?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Abug) or perhaps [open pull requests in `CottonMC/Cotton` which haven't been reviewed yet](https://github.com/search?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+repo%3ACottonMC%2FCotton+comments%3A0). To help you find issues and pull requests, each label is listed with search links for finding open items with that label in `CottonMC/Cotton` only and also across all Cotton repositories. We  encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

The labels are loosely grouped by their purpose, but it's not required that every issue have a label from every group or that an issue can't have more than one label from the same group.

Please tell us on the Cotton Discord server if you have suggestions for new labels, and if you notice some labels are missing on some repositories, then please open an issue on that repository.

#### Type of Issue and Issue State

| Label name | :mag_right: | Description |
| --- | --- | --- |
| `enhancement` | [search][search-cotton-org-label-enhancement] | Feature requests. |
| `bug` | [search][search-cotton-org-label-bug] | Confirmed bugs or reports that are very likely to be bugs. |
| `question` | [search][search-cotton-org-label-question] | Questions more than bug reports or feature requests (e.g. how do I do X). |
| `help wanted` | [search][search-cotton-org-label-help-wanted] | The Cotton team would appreciate help from the community in resolving these issues. |
| `good first issue` | [search][search-cotton-org-label-good-first-issue] | Less complex issues which would be good first issues to work on for users who want to contribute to Cotton. |
| `duplicate` | [search][search-cotton-org-label-duplicate] | Issues which are duplicates of other issues, i.e. they have been reported before. |
| `wontfix` | [search][search-cotton-org-label-wontfix] | The Cotton team has decided not to fix these issues for now, either because they're working as intended or for some other reason. |
| `invalid` | [search][search-cotton-org-label-invalid] | Issues which aren't valid (e.g. user errors). |

[search-cotton-org-label-enhancement]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Aenhancement
[search-cotton-org-label-bug]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Abug
[search-cotton-org-label-question]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Aquestion
[search-cotton-org-label-help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3A"help%20wanted"
[search-cotton-org-label-good-first-issue]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3"good%20first%20issue"
[search-cotton-org-label-duplicate]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Aduplicate
[search-cotton-org-label-wontfix]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Awontfix
[search-cotton-org-label-invalid]: https://github.com/search?q=is%3Aopen+is%3Aissue+user%3ACottonMC+label%3Ainvalid
[good-first-issue]: https://github.com/search?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+label%3A"good%20first%20issue"+user%3ACottonMC+sort%3Acomments-desc
[help-wanted]: https://github.com/search?q=is%3Aopen+is%3Aissue+label%3A"help%20wanted"+user%3ACottonMC+sort%3Acomments-desc
