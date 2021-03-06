---
title: "Adding to a Pull Request"
teaching: 0
exercises: 0
questions:
- "How do I make changes to an existing pull request?"
objectives:
- "Know how to make changes to an existing pull request"
keypoints:
- "Any changes to your feature branch in `origin` will be reflected in your PR automatically"
---
So you've made your pull request, but changes have been requested. How do you make them?

Let's take a look at the recent history of your git repository.
You have a feature branch which is ahead of `gh-pages`, which is the default branch
in the Carpentries' lesson repos, and is also the branch used to build the website.

All we need to do is to modify that feature branch, and the pull request will update.

The simplest (if not the most elegant solution) is to add more commits to the feature branch.
Then push your local branch to `origin` (your forked copy of the repo),
and your pull request updates.
Your new (or amended) commits show up in the PR on GitHub.

> ## Add to your pull request
> Suppose the reviewer has asked for changes to your pull request.
> Make those changes by adding another commit to the feature branch
> you used to submit the pull request.
> Then view your pull request on GitHub and check that the extra commit shows.
> You might need to refresh the GitHub page in your browser.
{: .challenge}
