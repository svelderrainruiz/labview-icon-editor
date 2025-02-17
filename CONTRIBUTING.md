1. <a href="#ossiconeditor">The Open Source LabVIEW Icon Editor</a>
1. <a href="#contributephilosophy">Our Contributing Philosophy</a>
1. <a href="#hotocontribute">How to contribute</a>
1. <a href="#collaboratewithni">Collaborate with the community and NI!</a>
1. <a href="#discussionnewfeature">Creating a discussion for a new feature</a>
1. <a href="#enhancements">Enhancements</a>
1. <a href="#reportingissues">Reporting issues</a>

<a name="ossiconeditor" />

# The Open Source LabVIEW Icon Editor

Just recently, the LabVIEW Icon Editor has been made open source to encourage collaboration between NI and the LabVIEW Community. Every new build of LabVIEW will grab the icon editor that has been pushed into the `main` branch from this repo.

The direction of the LabVIEW Icon Editor and which new features are added, and which are left out, is decided by the steering committee, which includes NI staff and LabVIEW community volunteers (sometimes referred to as a “cathedral” style of development).

That being said, the Icon Editor is great because of the LabVIEW users who use it, share their code with the community, and discuss ways to make LabVIEW even better. Some of the most important and undervalued work in open source is from non-code contributions, and that is where we can use the most help from you.

<a name="contributephilosophy" />

# Our Contributing Philosophy

This repo is managed via [git](https://git-scm.com), with the canonical upstream repository hosted on [GitHub](https://github.com/ni/labview-icon-editor) and it follows a pull-request model for development.

Feature requests are selected by NI in a joint effort with a group of members of the LabVIEW community called a "steering committee". A steering committee is a group of trusted individuals selected by the software community lead based on their background and contribution history to the NI ecosystem.

Steering committees are non-NI employees with triage roles to the repo that can vote on community driven features being part of the next LabVIEW release.

<a name="collaboratewithni" />

# Collaborate with the community and NI!

See below the list of activities (order by effort level) of how you can contribute:

| Contribution type | Effort level(1-10) |
|-------------------|--------------|
| <a href="#commentgithubissues">Comment on GitHub issues</a> |       1       |
| <a href="#commentgithubdiscussions">Comment on GitHub discussions</a> |       1       |
| <a href="#creategithubdiscussions">Create a GitHub discussion</a> |     2         |
| <a href="#reportanissue">Report an issue</a> |       2       |
| <a href="#developafeature">Develop a feature</a> |   8 to 10           |
| <a href="#solveabug">Solve a bug</a> |   5 to 10           |

<a name="commentgithubissues" />

## Comment on GitHub issues

Go to the [issues](https://github.com/ni/labview-icon-editor/issues) section of the repo and voice your opinion on issues that other people are having. Did you found a workaround to any of the GitHub issues? we want to hear about it! 

<a name="commentgithubdiscussions" />

## Comment on GitHub discussions

[GitHub discussions](https://github.com/ni/labview-icon-editor/discussions) are raw ideas in the process of gathering feedback from the community before converting them into a GitHub issue. Go to the GitHub discussions and voice your opinion on ideas that will eventually be a part of the next shipping version of the Icon Editor.

<a name="creategithubdiscussions" />

## Create a GitHub discussion

Is your idea not ready yet to mark it as a concrete issue with steps to reproduce? or a feature request with enough information?

Create a [GitHub discussion](https://github.com/ni/labview-icon-editor/discussions/new/choose) so that other member of the LabVIEW community can weigh in.

<a name="reportanissue" />

## Report an issue

Found an issue? raise a new GitHub issue and select "Bug Report"  https://github.com/ni/labview-icon-editor/issues/new/choose

<a name="developafeature" />

## Develop a feature

<a name="solveabug" />

## Solve a bug



<a name="enhancements" />

# Enhancements

If you have an idea or suggestion for an enhancement to the LabVIEW Icon Editor library, please use the [New Features](https://github.com/ni/labview-icon-editor/discussions/categories/new-features) discussion section. **please make sure to start a discussion about your changes.** The direction of the LabVIEW Icon Editor and which new features are added are discussed in our Discord Server and in [this GitHub discussions section](https://github.com/ni/labview-icon-editor/discussions/categories/new-features), and in the end, they are decided by the core team.

Talking to us first via the discussions section about the enhancement you want to build will be the most likely way to get your pull request into the library (see Our Contributing Philosophy above). We would hate to see you write code you’re proud of, just to learn that we’ve already been working on the same thing, or that we feel doesn’t fit into the core library.

Once your idea has been selected for the next release of LabVIEW, a branch will be created that you can submit your pull request to.

<a name="pwsh" />

# Creating a discussion for a new feature

The first step to start an enhancement to the icon editor is to create a discussion on the [New Features](https://github.com/ni/labview-icon-editor/discussions/categories/new-features) discussion board. You must describe the problem that made you want to have this enhancement.

<a name="pwsh" />

### 💫 Pull Requests

When submitting a PR, please follow these guidelines to ensure clarity and ease
of review:
 
1. **Title**: Start with a short, descriptive title that summarizes the change.
2. **Description**:
   - **Purpose**: Explain why you are making this change.
   - **Changes Made**: Describe what changes you made and why.
   - **Related Issues**: Reference any related issues using `#issue_number`.
   - **Testing**: Outline how you tested your changes and any specific areas of
     the code to focus on during review.
   
Please remember to sign off your commits (e.g., by using git commit -s if you
are using the command line client). This amends your git commit message with a
line of the form Signed-off-by: Name Lastname <name.lastmail@emailaddress.com>.
Please include all authors of any given commit into the commit message with a
Signed-off-by line. This indicates that you have read and signed the Developer
Certificate of Origin (see below) and are able to legally submit your code to
this repository.

<a name="reportingissues" />

### Reporting Issues
 
When creating an issue, please provide a detailed description to help us
understand the problem. Here are some tips:
 
1. **Title**: Use a clear, concise title that summarizes the issue.
2. **Description**:
   - **What Happened**: Describe the issue you encountered.
   - **Expected Behavior**: Explain what you expected to happen.
   - **Steps to Reproduce**: List the steps necessary to reproduce the issue.
   - **Environment**: Include relevant details about your environment (e.g.,
     operating system, LabVIEW version, etc.).
   - **Screenshots**: If applicable, add screenshots to clarify the issue.


All interactions should be done with care following our [Code of Conduct](https://github.com/ni/labview-icon-editor/blob/main/CODE_OF_CONDUCT.md).