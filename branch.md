#branch
```
切换到
$ git checkout commitBranch
```

```
建立追踪关系，在现有分支与指定的远程分支之间
$ git branch --set-upstream origin/practice1

The --set-upstream flag is deprecated and will be removed. Consider using --track or --set-upstream-to
Branch origin/practice1 set up to track local branch commitBranch.

If you wanted to make 'commitBranch' track 'origin/practice1', do this:

    git branch -d origin/practice1
    git branch --set-upstream-to origin/practice1
```

