# homework
1. How do you see the files changed within each commit from git log?
To find out which files changed in a given commit, use the git log --raw command. It's the fastest and simplest way to get insight into which files a commit affects.

2. How do you see the contents of what changed within each file from the git log?
Using git log --follow -p bar will show the file's entire history, including any changes to the file when it was known as foo . The -p option ensures that diffs are included for each change. --stat is also helpful. You can use it together with -p.

3 .What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
HEAD means current branch. When switching branches, the HEAD changes to point to the tip of the new branch.


