
## About the project

This project aims to automatically discover the higher-level semantics of C++ classes by classifying the classes as abstractions, such as, stacks and queues.

### Current status

#### First prototype

Currently, the project is in the prototyping stage. The aim is to do an initial implementation of the algorithm design.

### Repository

- `research/abstractionAnalysis/` directory contains all implementations and necessary files for this project
- `research/abstractionAnalysis/testfiles` directory contains test input files and expected outputs
- `research/abstractionAnalysis/semantics` directory contains semantic specification files used by the parser

## Steps

- Download POET
  - [Repository](https://github.com/qingyi-yan/POET)
  - Place the downloaded `POET` directory in the same directory as `abstraction-analysis`
  - Alternatively, you may update the `POET_HOME` variable in the Makefile to point to your `POET` directory location
- Install POET following the directions in the [Handbook](http://www.cs.uccs.edu/~qyi/poet/documents/manual.pdf)
- Go to the `research/abstractionAnalysis/` directory and run `make all` or
  - `make stack` to only analyze the given Singly Linked List against a stack abstraction
  - `make queue` to only analyze the given Singly Linked List against a queue abstraction

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
