# Main commands III

* `git checkout` - change a branch or update local files according to the version included in index file. Used at any time when there is a need to test the data functionality or refresh the workspace content.

```bash
git checkout –b <branch_name>
```

* `git merge` - the combination of different solutions (branches) into one source code. Used during the code integration.

```bash  
git merge <branch_name>/master
```

* `git rebase` - the alternative way to git merge ir rebasing. Used for the combination of different solutions (branches) into one source code during the code integration.

More info about rebase vs merge can be found under link:

[https://www.atlassian.com/git/tutorials/merging-vs-rebasing](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)

You also need to remember the golden rule of rebase:

**Do not rebase public banches!!!**
