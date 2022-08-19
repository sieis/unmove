# Contributing to unMove

## Introduction

> Thank you so much for contributing to the project! This is my first open-source library, and it's been a joy to create. Your contributions are invaluable! :blush:

## Read these guildlines

> Following these guidlines helps me more quickly address issues and implement your contributions.

## Types of contributions

> unMove is a small, early-stage library. 

I am currently looking particularly for:

* new, clean css animations
* docs site improvements

This will expand as the project moves out of its infancy.

## Ground Rules

> Code of Conduct forthcoming

### Empathy > Code

* Be respectful in all communication. 


* When adding classes, follow naming convention by begin each with `um-` followed by a one or two word descriptor. Be as concise as possible. i.e. `class="um-spin-fast"`

## Your first contribution

> Look through the open issues. I'm a beginner myself, so most everything should be beginner friendly. If you would like to contribute a class for the animations, do so one at a time to build your confidence.

Make sure to test, test, test before submitting a pull request.

### No idea where to start?

Here's a step by step of what the process should look like

1. Fork the repository, clone your fork and configure remotes:

```bash
# Clone your fork of the repo into the current directory
git clone https://github.com/<your-username>/unmove.git
# Navigate to the newly cloned directory
cd unmove
# Assign the original repo to a remote called "upstream"
git remote add upstream https://github.com/sieis/unmove.git
```

2. If you did that a while back, get the latest changes:

```bash
git checkout main
git pull upstream main
```

3. Create a new branch from the main branch to contain your feature, change or fix:

```bash
git checkout -b <your-branch-name>
```

4. Commit the changes.

5. Locally merge (or rebase) the upstream development branch into your topic branch:

```bash
git pull [--rebase] upstream main
```

6. Push your topic branch to your fork:

```bash
git push origin <topic-branch-name>
```

7. Open a pull request with a clear title and description against the main branch.