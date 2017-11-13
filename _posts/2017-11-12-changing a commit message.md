---
layout: post
title: GitHub - Changing a commit message
---

![github]({{ site.baseurl }}/images/github-logo.png)

If a commit message contains unclear, incorrect, or sensitive information, you can fix it locally and push a new commit with a new message to GitHub.

### Commit has not been pushed online

If the commit only exists in your local repository and has not been pushed to GitHub, you can amend the commit message with the `git commit --amend` command.

- On the command line, navigate to the repository that contains the commit you want to amend.

- Type `git commit --amend` and press **Enter**.

- In your text editor, edit the commit message and save the commit.

The new commit and message will appear on GitHub the next time you push.

### Amending the message of the most recently pushed commit

    - Follow the steps above to amend the commit message.

    - Use the `push --force` command to force push over the old commit.

```ssh 
git push --force example-branch
```

> [Source](https://help.github.com/articles/changing-a-commit-message/)

