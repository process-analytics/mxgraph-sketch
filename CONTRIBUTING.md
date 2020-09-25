# Contributing

You are here to help on `mxgraph-sketch`? Awesome, feel welcome and read the following guidelines in order to know how to contribute, to ask questions and to make `mxgraph-sketch` such a great tool.

All members of our community are expected to follow our [Code of Conduct](https://github.com/process-analytics/.github/blob/main/CODE_OF_CONDUCT.md). Please make sure you are welcoming and friendly in all of our spaces.

## Contributions 

There are many ways to contribute:

- help people with the questions they ask on the [Github Issues](https://github.com/process-analytics/mxgraph-sketch/issues)
- submitting bug reports and feature requests in the [Github Issues](https://github.com/process-analytics/mxgraph-sketch/issues/new)
- writing code which can be incorporated into `mxgraph-sketch` itself
- improving the documentation

## Code and documentation changes guidelines

For all contributions, please respect the following guidelines:

1. If you've noticed a bug or have a feature request, let us know in the [GitHub Issue tracker](https://github.com/process-analytics/mxgraph-sketch/issues/new )! So we can confirm the bug or approve your feature, and provide feedback, before starting to code :slightly_smiling_face:

2. Do the changes in your own [fork](CONTRIBUTING.md#fork--create-a-branch) of the code

3. Do not commit changes to files that are irrelevant to your feature or bugfix (eg: `.gitignore`).

4. Provide tests and documentation whenever possible.

5. Be sure you have followed the [code style](https://github.com/process-analytics/bpmn-visualization-js/blob/master/docs/development/development.md#code-style) for the project.

6. Prior opening a Pull Request, ensure the build is fully working by locally running `npm run all` (build, check and
test everything)

7. Open a [GitHub Pull Request](./docs/development/pull-request.md#open-a-pull-request) with your patches. (**1** pull request = **1** feature or bug)
   We will review your contribution and respond as quickly as possible. Keep in mind that this is an open source project, and it may take us some time to get back to you. Your patience is very much appreciated.

8. If this is your 1st Pull Request, sign the [Contributor License Agreement](./docs/development/pull-request.md#sign-the-contributor-license-agreement)

9. Be willing to accept criticism and work on improving your code. 

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on  GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)    

### Fork & create a branch

[Fork mxgraph-sketch](https://help.github.com/articles/fork-a-repo) and create a branch with a descriptive name. 

A good branch name would be (where issue #25 is the ticket you're working on): **25-annotations_to_tasks**

```sh
git checkout -b 25-annotations_to_tasks
```

### IDE configuration

The repository contains configuration for [Eclipse Theia](https://theia-ide.org/) and [gitpod.io](https://www.gitpod.io/).

### Development

:warning: **TO WRITE** :warning: 

### Commit in the Pull Request
There is no convention for the commit message in the Pull Request.
The most important part is the title of the Pull Request, because:
- Everyone must use Pull Request, no direct commit allowed on main branch
- The commits of a Pull Request are almost always squashed
- The title of the Pull Request is used as proposal for the maintainer merging the Pull Request

### Open a Pull Request

At this point, you should switch back to your main branch and make sure it's up to date with `mxgraph-sketch`
`main` branch:

```sh
git remote add upstream git@github.com:process-analytics/mxgraph-sketch.git
git checkout main
git pull upstream main
```

Then update your feature branch from your local copy of main, and push it!

```sh
git checkout 25-annotations_to_tasks
git rebase main
git push --set-upstream origin 25-annotations_to_tasks
```

Finally, go to GitHub and [make a Pull Request](https://help.github.com/articles/creating-a-pull-request) ​with labels :smile:
For the title, follow the directives of the Pull Request template.

:warning: ​We care about quality. So your PR won't be merged until all tests pass.

### Sign the Contributor License Agreement

By signing the CLA, we acknowledge that your contribution is accepted as it and that you cannot be held responsible for
any impacts on its integration. You then grant us the right to modify and distribute your code without restrictions. We
ask this of all contributors in order to assure our users of the origin and continuing existence of the code.

When you contribute to the project on GitHub with a new pull request, the [cla-assistant bot](https://cla-assistant.io/)
will evaluate whether you have signed the CLA. If required, the bot will comment on the pull request, including a link
to this system to accept the agreement.

You only need to sign the CLA once or when the CLA terms have changed.

### Keeping your Pull Request updated

If a maintainer asks you to [rebase](http://git-scm.com/book/en/Git-Branching-Rebasing) your PR, they're saying that a lot of code has changed, and that you need to update your branch so it's easier to merge.

Here's the suggested workflow:

```sh
git checkout 25-annotations_to_tasks
git pull --rebase upstream main
git push --force-with-lease 25-annotations_to_tasks
```

At this point, you're ready to make your changes! Feel free to ask for help. Everyone is a beginner at first :smile_cat:


## Maintainers

### Merging a PR (maintainers only)

A PR can only be merged into main by a maintainer, if all of these conditions are met:

* It is passing CI.
* It has been approved by at least two maintainers. If it was a maintainer who opened the PR, only one extra approval is needed.
* It has no requested changes.
* It is up to date with current main.

### Release (maintainers only)

Maintainers need to do the manual following actions **in the order described here** to push out a release (the release
automation is a work in progress).

#### Git Tag

:warning: **TO WRITE** :warning:
