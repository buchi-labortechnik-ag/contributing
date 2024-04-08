# Contributing to Buchi

Thanks for your interest in contributing to Büchi! :tada: We value everybody's contribution.

# Table of Contents
1. [Contribute!](#contribute)
2. [Naming Conventions](#naming-conventions)
3. [Other ways to contribute](#other-ways-to-contribute)
4. [Code of conduct](#code-of-conduct)

## Contribute! (Pull Request) <a name="contribute" />

Before you start, we strongly recommend searching for existing PRs and issues to see if the issue has already been reported.

**For external collaborators**, we are adhering to the [Fork and pull collaboration model]([url](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models#fork-and-pull-model))

* Fork Buchi's repo and clone it onto your computer

```
$ git clone git@github.com:<your Github handle>/<buchirepo.git>
$ cd <repo's folder>
$ git remote add upstream <buchis repo>
```

* Create a new branch, for example:

```
$ git checkout -b fix-buchi-bug
```

* Work on the branch you created

* Check if your code is aligned with our code review guidelines

* Once you're happy with the changes, commit the changes based on our commit style

```
$git add <modified_file>
```

* Sync your copy of the code with the original repository. This way you can check for changes:

```
$ git fetch upstream
$ git rebase upstream/master
```

* Push the changes to your account

```
$ git push -u origin <changes-name>
```

* Get a PR merged! :1st_place_medal: ([click here for more details about creating a PR from a fork]([url](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)))

**For internal collaborators**, we are using the [Shared repository collaboration model]([url](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/about-collaborative-development-models#shared-repository-model))

* Create an issue or start from an existing issue (every PR should be linked to a single issue - there is a many-to-one relation between PRs and issues)
* Clone the repository locally
```
$ git clone git@github.com:<your Github handle>/<buchirepo.git>
$ cd <repo's folder>
```

* Create a new branch ([see the Branch name policy]([url](https://github.com/buchi-labortechnik-ag/contributing/edit/main/README.md#naming-your-branch)))
```
$ git checkout -b fix-buchi-bug
```

* Work on the branch you created
* Check if your code is aligned with our code review guidelines
* Once you're happy with the changes, create one or more commits
* Make sure the commits follow our [Commit guidelines]([url](https://github.com/buchi-labortechnik-ag/contributing/edit/main/README.md#naming-your-commit))

```
$git add <modified_file>
$git commit -m "fix(plots): fixed plots html rendering"
```
* Sync your copy of the code with the original repository. This way you can check for changes:

```
$ git fetch
$ git pull
```

* Push the changes to the remote branch

```
$ git push -u origin <changes-name>
```

* Get a PR merged! :1st_place_medal:

## Naming Conventions <a name="naming-conventions" />

We follow the [Conventional Commit guidelines](https://www.conventionalcommits.org/en/v1.0.0/#summary):

* Max. length: 70 characters (including spaces)
* Descriptive
* Lower case
* No punctuation
* Include our types of commit

### Types <a name="types" />

* feat: A new feature
* fix: A bug fix
* docs: Documentation only changes
* style: Changes that do not affect the meaning of the code (white space, formatting, missing semi-colons, etc)
* refactor: A code change that neither fixes a bug nor adds a feature
* perf: A code change that improves performance
* test: Adding missing tests or correcting existing tests
* build: Changes that affect the build system or external dependencies
* ci: Changes to our CI config­uration files and scripts
* chore: Other changes that don't modify src or test files
* revert: Reverts a previous commit

The commit example should be structured as follows:

```
<type>[optional scope]: <description>
```

### Naming your commit <a name="commit-naming" />

#### Commit Message Examples

##### Good Example

```
fix(plots): fixed plots html rendering
refactor(upload-get): refactor upload-get function to upload-post
docs: documented every function in comments
feat(parser): add ability to parse arrays 
```

##### Bad Examples

Commit name | Feedback
------------ | -------------
Fixed plots functions | Doesn't follow style
Changed upload-get function |  No style, no descriptive
DOCs update | All letters should be lowercase 
Fixed plots functions that return the HTML file rendered in different formats | Too long


### Naming your branch <a name="branch-naming" />

Your branch name should follow the format type-scope(-issue_id):

* type is one of the types above
* scope is optional, and represents the module your branch is working on
* issue_id is the GitHub issue number

#### Branch Names Examples

Your branch name should follow the format `type-scope(-issue_id)`:

* type is one of the types above
* scope is optional and represents the module your branch is working on
* issue_id is the GitHub issue number

##### Good Examples

```
fix-plots-render-1
feat-array-parser
docs-add-functions-description
```

##### Bad examples

Branch name | Feedback
------------ | -------------
FIX-PLOTS1 | Not descriptive enough, all caps, doesn't follow the format
my-branch-1 | Not descriptive, wrong format


## Other ways to contribute <a name="other-ways-to-contribute" />

Collaborations in a podcast, invitations to a meetup, or anything else to share Buchi's work is also very valuable to us 	:handshake:


## Code of conduct <a name="code-of-conduct" />

Buchi adheres to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct/). By participating, you are expected to uphold this code.
