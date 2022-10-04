# Get Going with Git!

This is a quick course to start using version control with git. 

### _What is version control?_

Version control, also known as revision control, is a software program that allows us to track distributed changes to information/code over time. Git is an example of a version control implementation. Changes are "distributed" when they come from many different sources. For instance, if a team of developers is all making changes to the same code, or if you have a different branch of evolution that has resulted in changes to a single original genome. We can use version control to "revert" or rewind back to an older version of the information/code, "merge" an updated version into our copy, "push" our changes to a "master" copy and do much more. Let's get set up to travel through time and alternative versions of reality via version control! 🚀

### 1. Getting Started

First, create an account on github! This site! ^ :octocat:

_PSA: You don't need to use your school username_

_**Now open up your terminal! 🤠**_

1. Follow these instructions to check if you have `git` installed on your machine and install it if you don't: https://github.com/git-guides/install-git
2. Use `cd` to navigate to the directory that you want to store your code in. (I like to have a `~/Development` folder, for example)
3. Download this code repository using `git clone git@github.com:morgansierrasnyder/git-going.git`
4. Use `cd git-going` to navigate into the directory that now contains the repository

**Note:** if you get an error that says, "Support for password authentication was removed on August 13, 2021", you may need to use an SSH key for authentication. Here are the steps for that:
1. Create an SSH key by typing ssh-keygen into Terminal. I recommend saving it in the default location, `~/.ssh/id_rsa` A passphrase is optional, but recommended.
2. Go to the directory where you saved your SSH key; `cd ~/.ssh` is the default 
3. Show the contents of your key `cat id_rsa.pub`
4. Copy this entire string, including the "ssh-rsa" at the beginning and your email address or username at the end.
5. Go to Github. In the upper right corner, click on the down arrow next to your user icon. Click Settings. Go to SSH and GPG keys. Click "New SSH key" and paste the contents of your public key, along with a title of your choice.
6. You may need to wait ~5 minutes for your key to get propagated to all the servers; then you should be able to access the repositories you have access to.


You're now ready to make new versions of this code!

(_Or lack there of... It's so empty in here that I think I saw a tumbleweed blow by 🌪️🌵_)

_**Hold up 🛑: Group demo: Basic git commands**_

### 2. Contributing

Review the basic git commands on the cheatsheet.
There are many more resources on the internet that go into deeper explanations of each command, but here are a few solid ones:
- [Bitbucket: basic git commands](https://confluence.atlassian.com/bitbucketserver/basic-git-commands-776639767.html)
- [10 git commands every developer should know](https://www.freecodecamp.org/news/10-important-git-commands-that-every-developer-should-know/)

1. Create a new markdown file (file extension `.md`). You can make a copy of this one.
2. Commit your file: `git add <your-file>` and `git commit -m "replace this with a message that describes your file!"`
3. Push your changes to the remote repository (this one here, on the internet!): `git push`

### 3. Collaborating

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
