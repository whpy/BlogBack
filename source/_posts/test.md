---
title: test
date: 2024-02-13 00:02:16
tags:
---

## Abstract 
this is a simple file just for test.

## Results
successfully generate a blog in markdown format; Successfully synchronize the blog contents with the remote repository; discard the unused blog files.

## Conclusions
All the following commands are run on the git bash installed on windows:
1. **New a file** 
```(bash)
hexo new "test"
```

2. **Generate related files**
```(bash)
hex g
```

3. **Synchronize(deploy) the files to remote github repo**
```(bash)
hexo d
```

4. **Delete Unneeded blog**
Firstly, delete the markdown files in the source. Then, we run:
```(bash)
hexo d -g
```

5. **create folder for draft**

```(bash)
hexo n draft "$(name_of_draft)"
```
