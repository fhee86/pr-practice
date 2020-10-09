# PR Practice &middot; [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

## Clone the repository

Now clone the forked repository to your computer. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command: `git clone {link to your fork}`

## Create a branch

Change to the repository directory on your computer (if you are not already there): `cd pr-practice`

Now create a branch using the git checkout command:`git checkout -b your-new-branch-name`

For example: `git checkout -b add-adam-to-contributors`

The name of the branch does not need to have the word add in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to the `contributors.md` file.

## Make changes and commit those changes

Now open `contributors.md` file in a text editor, add your name to it.

> Don't worry about permanence, you can submit a pull request to delete your name later if you would like :key:

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the git add command: `git add contributors.md`

Now commit those changes using the git commit command:

`git commit -m "Add {name} to contributors"`

replacing {name} with your name.

## Push changes to GitHub

Push your changes using the command git push: `git push origin {your-branch-name}`

replacing {your-branch-name} with the name of the branch you created earlier.

## Submit your changes for review

If you go to your forked repository on GitHub, you'll see a Compare & pull request button. Click on that button.

Add a title to your pull request and click Create pull request.

## Summary

You have just completed the standard GitHub workflow:

`fork -> clone -> edit -> pull request` :test_tube:
