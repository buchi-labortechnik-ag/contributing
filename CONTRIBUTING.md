# Contributing to Buchi

Thanks for your interest in contributing to Büchi! :tada: We value everybody's contribution.

## How to contribute?

[To define]


## Contribute! (Pull Request) 

Before you start, we strongly recommend you to search on existing PR's and issues to see if the issue has already been reported.

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

* Push the changes to your accont

```
$ git push -u origin <changes-name>
```

* Get a PR merged! :1st_place_medal:


## Naming Conventions

We follow the [Conventional Commit guidelines](https://www.conventionalcommits.org/en/v1.0.0/#summary):

* Max 70 characters
* Desciptive
* Lower case
* No punctuation
* Include our types of commit

### Types

* build: Changes that affect the build system or external dependencies
* docs: Documentation only changes
* feat: A new feature
* fix: A bug fix
* perf: A code change that improves performance
* refactor: A code change that neither fixes a bug nor adds a feature
* style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* test: Adding missing tests or correcting existing tests

The commit example should be structured as follows:

```
<type>[optional scope]: <description>
```

### Naming your commit

#### Commit Message Examples

##### Good Example

```
fix(plots): fixed plots html renderization
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
Fixed plots functions that returns the html file renderized in different formats | Too long


### Naming your branch

Your branch name should follow the format type-scope(-issue_id):

* type is one of the types above
* scope is optional, and represents the module your branch is working on
* issue_id is the GitHub issue number

#### Branch Names Examples

Your branch name should follow the format `type-scope(-issue_id)`:

* type is one of the types above
* scope is optional, and represents the module your branch is working on.
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
FIX-PLOTS1 | Not descriptive enough, all caps, doesn't follow style
my-branch-1 | Not descriptive, no style


## Other ways to contribute

Collaborations in a podcast, invitations to a meetup or anything else to share Buchi's work is also very valuable to us 	:handshake:


## Code of conduct

Buchi adheres to the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/1/4/code-of-conduct/). By participating, you are expected to uphold this code.