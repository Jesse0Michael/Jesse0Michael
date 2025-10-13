# Git

Contributions should be done in short-lived **branches** and committed through pull requests.

### Commits
Commits should be **Atomic**. Each commit should represent a single logical change so that it can be easily understood, reviewed, and reverted if necessary.

Commit messages should describe the **what** of the change. 

> A plethora of commits with the message "fix", "fix again", "fix for real this time" are not useful to anyone. Same for the commit messages "pr feedback", "review changes", "address comments".

Commit messages should follow the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/#summary) format.  
Conventional commits provide a quick reference to the scope of the change and can be used to automate the generation of changelogs and versioning.

> [amending commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/changing-a-commit-message#amending-older-or-multiple-commit-messages) is a great way to keep your commit history clean and useful. 



### Pull Requests

Pull requests are the best place for discussion, **NOT** slack. The history of the discussion would be preserved in the pull request, referenced by the commit, so that future developers can understand the context of the change.

Pull requests should describe the **why** of the change.

Run **tests** and **linters** automatically through CI.

Pull requests should be small, ideally less than 500 lines of *meaningful* code changes.

> Meaningful code changes exclude formatting or whitespace changes. It also excludes generated code changes, which should be in its own commit or PR.
