# git-tools
Scripts to assist with common git functions

## Usage
Place these bash scripts in somewhere in your path, and execute them from your command line as needed.

## Tools
### git-branch-prune
#### Description
This tool is a useful cleanup tool can be used to remove local references to remote origins that no longer exist.
#### Usage
`git branch-prune`
#### Example Output
```
=== Switching to master branch...
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
Already up to date.
=== Pruning remote branches from origin...
Pruning origin
URL: https://github.com/darkagn/data-structures.git
 * [pruned] origin/bugfix/fix-bug-in-binary-tree
 * [pruned] origin/feature/add-red-black-tree
=== Pruning local branches that are deleted from origin...
Deleted branch feature/add-red-black-tree (was 41ca385f074).
=== Returning to original branch...
Switched to branch 'development'
Your branch is up to date with 'origin/development'.
Already up to date.
=== Done.
```
