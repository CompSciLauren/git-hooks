# git-hooks
How to use git hooks - resources and examples.

## What are git hooks?
> "Like many other Version Control Systems, Git has a way to fire off custom scripts when certain important actions occur. There are two groups of these hooks: client-side and server-side. Client-side hooks are triggered by operations such as committing and merging, while server-side hooks run on network operations such as receiving pushed commits. You can use these hooks for all sorts of reasons." - [git-scm.com](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)

## Overview of Samples
This repo contains the following samples:

**_pre-commit samples_**
- **format-code:** Run command to format code and re-add any files modified after formatting
- **search-term:** Fail commit if a specific term is found in the code
- **verify-name-and-email:** Fail commit if user.name or user.email is incorrect

**_miscellaneous samples_**
- **default samples:** samples that are automatically generated in .git/hooks

## Helpful Hints
You can bypass pre-commit hooks by adding `--no-verify` to end of `git commit` command

## Resources
Below are a variety of helpful resources on how git hooks work.

### Video
[Git hooks and practical uses. Yes, even on Windows.](http://www.youtube.com/watch?feature=player_embedded&v=fMYv6-SZsSo&t=240s)

### Articles
[An Introduction to Git Hooks](https://www.sitepoint.com/introduction-git-hooks/)

[Git hooks and practical uses. Yes, even on Windows.](https://www.tygertec.com/git-hooks-practical-uses-windows/)

[Easy git hooks with husky](https://www.vojtechruzicka.com/githooks-husky/)

[Git Hooked](https://www.javascriptjanuary.com/blog/git-hooked "Git Hooked")

[Automate Your Workflow with Git Hooks](https://hackernoon.com/automate-your-workflow-with-git-hooks-fef5d9b2a58c)

[Using JavaScript in Your Git Hooks](https://medium.com/@Sergeon/using-javascript-in-your-git-hooks-f0ce09477334 "Using JavaScript in Your Git Hooks")

### Book
[Git Pro by Scott Chacon and Ben Straub](https://git-scm.com/book/en/v2)
