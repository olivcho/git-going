# Get Going with Git!

This is a quick course to start using version control with git. 

### Getting Started

First, create an account on github! This site! ^ :octocat:
_PSA: You don't need to use your school username_


_**Open up your terminal! 🤠**_

1. Follow these instructions to check if you have `git` installed on your machine and install it if you don't: https://github.com/git-guides/install-git
2. Use `cd` to navigate to the directory that you want to store your code in. (I like to have a `~/Development` folder, for example)
3. Download this code repository using `git clone git@github.com:morgansierrasnyder/git-going.git`
4. Use `cd git-going` to navigate into the directory that now contains the repository

You're now ready to make new versions of this code!
_Or lack there of... It's so empty in here that I think I saw a tumbleweed blow by 🌪️🌵_

### 🛑 Group demo: Basic git commands

### Contributing

Review the basic git commands on the cheatsheet.
There are many more resources on the internet that go into deeper explanations of each command, but here are a few solid ones:
- [Bitbucket: basic git commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
- [10 git commands every developer should know](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)

1. Create a new markdown file (file extension `.md`). You can make a copy of this one.
2. Commit your file: `git add <your-file>` and `git commit -m "replace this with a message that describes your file!"`
3. Push your changes to the remote repository (this one here, on the internet!): `git push`

### Collaborating

_**Get into a group of four! 🔢**_

1. Decide in your group on one file from this repository to edit
2. Each person should edit the file locally
3. Each person should push their changes to the remote repository

_What happened?_
#### Conflicts! ⚔️

Learn about different strategies for resolving conflicts here: [Resolving a merge conflict using the command line](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)

We'll talk about the difference between `git merge` and `git rebase`, which will help us avoid messy conflicts in the future!

## Now git going!

Pick a directory that's already on your computer, and version control it!

I like using the [Github desktop app](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop) for this, but you can also use `git init` in the command line.
