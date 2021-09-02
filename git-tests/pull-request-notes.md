# Git Pull Requests

A **pull request** is a way to reconcile and fold many peoples' changes into 1.
A **pull request** basically answers the question of "What did you change?"
Here is a [useful read about forking](https://www.toolsqa.com/git/difference-between-git-clone-and-git-fork/). Here is the [git documentation on PRs](https://git-scm.com/docs/git-request-pull). Unlike these notes, it includes the commands to use.

## Main points of PRs

1. Chance to get feedback on changes
2. Allows you to contribute to source that u don't own
3. Makes it clear to all that u changed something
4. Creates an environment for you and ur peers to discuss changes

## Process of a PR

Before anything, we need to make a **branch**. A **branch** is a copy of the OG
source, but one that we can chang w/out affecting the master branch. Cave Speak:
change on branch no change OhGee. Everytime a change is made on a branch, we
need to undergo a formal process to merge said changes:

1. Make [branch](https://www.atlassian.com/git/tutorials/using-branches)
   - Here's additional reading on [branches](https://www.freecodecamp.org/news/git-clone-branch-how-to-clone-a-specific-branch/)
2. Make changes
3. Pull latest master source
4. Submit PR
5. Someone [merges](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging) PR branch to master

A PR is a request for reviewers to look at changes and decide to deny or approve
them.

## Why PRs

- Peer Reviews
- Constructive Feedback
- Keep source code healthy
- Nip bad practices or suggest better solns
- Flag any problems in source

## To push all changes including deletes use:

1. `git add -A`
2. `git commit`
3. `git push`
