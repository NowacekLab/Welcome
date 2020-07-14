# Lesson 1 (A pre-tutorial tutorial)

## Getting set up with GitHub and GitHub Desktop
<!-- 1. Check to see if you have git already installed on your [Mac](http://modulesunraveled.com/installing-git/checking-see-if-you-already-have-git-installed-mac) or [Windows](http://modulesunraveled.com/installing-git/checking-see-if-you-already-have-git-installed-windows-machine) machine -->
1. Make a [GitHub](https://github.com/) account (you should have one if you are viewing this)
2. Join the [Nowacek Lab](https://github.com/NowacekLab) organization (you should have already if you are viewing this)
3. Download [GitHub Desktop](https://desktop.github.com/)
4. Login into your GitHub account in GitHub Desktop
5. Optional: (if you want to work in the command line) [Download](https://git-scm.com/) and install Git onto your machine

### Some basics

Git is a thing that exists independently of GitHub. By itself, Git is a version control protocol that can be executed through the terminal or a GUI. This means is that you can have the full git experience with commits, branches, merges, etc without ever using something like GitHub. Keep in mind that in this case your Git repository would exist only locally (aka on your computer) and this is called a **local repository**.

GitHub is a Git repository hosting service that allows you to keep track of and share your Git version control projects outside of your local computer/server and maintain a **remote repository**. The purpose of a remote repository (like GitHub) is to publish your code to the world (or to some people) and allow them to read or write it. The remote repository is only involved when you git push your local commits to a remote repository, or when you git pull someone else's commits from it.

### Some Git terms explained 
(adapted from linuxacademy.com)

***Branch***
A version of the repository that diverges from the main working project. Branches can be a new version of a repository, experimental changes, or personal forks of a repository for users to alter and test changes.

***Clone***
A clone is a copy of a repository or the action of copying a repository. When cloning a repository into another branch, the new branch becomes a remote-tracking branch that can talk upstream to its origin branch (via pushes, pulls, and fetches).

***Fetch***
By performing a Git fetch, you are downloading and copying that branch’s files to your workstation. Multiple branches can be fetched at once, and you can rename the branches when running the command to suit your needs.

***Fork***
Creates a copy of a repository.

***HEAD***
HEAD is a reference variable used to denote the most current commit of the repository in which you are working. When you add a new commit, HEAD will then become that new commit.

***Master***
The primary branch of all repositories. All committed and accepted changes should be on the master branch. You can work directly from the master branch, or create other branches.

***Merge***
Taking the changes from one branch and adding them into another (traditionally master) branch. These commits are usually first requested via pull request before being merged by a project maintainer.

***Origin***
The conventional name for the primary version of a repository. Git also uses origin as a system alias for pushing and fetching data to and from the primary branch. For example, git push origin master, when run on a remote, will push the changes to the master branch of the primary repository database.

***Pull/Pull Request***
If someone has changed code on a separate branch of a project and wants it to be reviewed to add to the master branch, that someone can put in a pull request. Pull requests ask the repo maintainers to review the commits made, and then, if acceptable, merge the changes upstream. A pull happens when adding the changes to the master branch.

***Push***
Updates a remote branch with the commits made to the current branch. You are literally “pushing” your changes onto the remote.

***Remote***
A copy of the original branch. When you clone a branch, that new branch is a remote, or clone. Remotes can talk to the origin branch, as well as other remotes for the repository, to make communication between working branches easier.

***Repository (“Repo”)***
In many ways, you can think of a Git repository as a directory that stores all the files, folders, and content needed for your project. What it actually is, is the object database of the project, storing everything from the files themselves, to the versions of those files, commits, deletions, et cetera. Repositories are not limited by user, and can be shared and copied (see: fork).

<br>
<br>

Hopefully by the end of this tutorial you feel less like this...
<p align="center">
  <img src="https://imgs.xkcd.com/comics/git.png" />
</p>

<br>

## On to the [next lesson!](https://github.com/NowacekLab/Welcome/blob/master/lesson2.md)
