# Clean History demo

To better read the git history of a repository it is sometimes useful to squash commits together. This is especially useful when working on a feature branch that has a lot of commits. This demo showcases how to squash commits together. To read more about squashing commits, see [this](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History) link. We do not recommend squashing commits on the main branch, but instead on feature branches as they are merged into the main branch.

The new squashed commit will have a new commit hash, so it is important to note that this will change the commit history of the repository. This is why we recommend squashing commits on feature branches that are merged into the main branch.

Now I want to test squashing and rebasing when approving a pull request.

## Testing _squashing and rebasing pull request_ summary feature

This is a test to see if the PR summary feature works when squashing and rebasing commits.

## Cleanup remote branches

To cleanup remote branches that have been merged into the main branch, run the following command:

```bash
git fetch --prune
```

## Cleanup local branches

To clean up a local branch that have been merged into the remote main branch, run the following command:

```bash
git branch -D <branch_name>
```
