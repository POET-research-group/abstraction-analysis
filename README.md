
## About the project

[Brief explanation of goal of project]

### Current status

#### First prototype

[Brief description of current status]

### Repository

- `research/abstractionAnalysis/` directory contains all implementations and necessary files for this project
- `research/abstractionAnalysis/testfiles` directory contains test input files and expected outputs
- `research/abstractionAnalysis/semantics` directory contains semantic specification files used by the parser
- `research/abstractionAnalysis/design` directory contains initial prototype design files (should it be included in public repository?)

## Steps

- Install POET (if you don't have it in your local machine already)
  - [Repository](https://github.com/qingyi-yan/POET)
  - [Handbook](http://www.cs.uccs.edu/~qyi/poet/documents/manual.pdf)
- Go to the `research/abstractionAnalysis/` directory and run `make all`
  - Run `make stack` to only analyze the given Singly Linked List against a stack abstraction
  - Run `make queue` to only analyze the given Singly Linked List against a queue abstraction

## Contribution guidelines

- Do not work on the `main` branch. Choose to use a working branch instead
- Commit locally often
- Rebase before pushing to remote
- When ready for review, open a pull request (PR) to merge to the `main` branch: try to keep each PR limited in scope and goal
- Once PR is open
  - Keep each incremental commit to let reviewers see commits as comments get addressed
  - Reviewer(s) will mark issues as **Resolved**
  - Requestor will merge once at least 2 reviewers have approved the request
- When approved for merging, do one final rebase to squash all comments from PR: keep 1 commit per PR
