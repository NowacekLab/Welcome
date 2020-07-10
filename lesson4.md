# Lesson 4

## Creating repositories

### Ways to create a repository 

We also may have code that we want to contribute to the repository for others to use OR we may want to work on a new project collaboratively.  There are a few ways to start a new repo, each of which may be more useful depending on the way your project may already exist locally.

**Option #1: Starting on GitHub (remote first, then local)**

1. Click "New"
2. Give your repository a name, description, and initialize with a README
3. Follow the instructions in the "Ways to access a repository" to add this repository to your GitHub Desktop and create a local repository
4. Add files through the normal File Explorer and edit files through any IDE/text editor

**Option #2: Starting in GitHub Desktop (remote and local kinda simultaneously)**

1. Click "File," "New Repository"
2. Give your repository a name, description, set the path for the local repository, and initialize with a README
3. Publish the repo to GitHub 

**Option #3: Starting in terminal, then GitHub Desktop (local then remote)**

FYI, your gonna have to use the terminal/Git Bash for this one. Mac people you'll want to open your terminal, Windows people search for Git Bash in your search bar and open it.

When you start messing with the command line there are some **key** commands you need to know. I think the command line is where people tend to get a little freaked out, but if you have these commands in your back pocket you'll be fine. 

**`pwd`** Print working directory. This tells you where you are in your folder structure. 

**`ls`** List stuff (idk if this is what it actually means but this is always what I say in my head). This will show you all of the files in the current folder. 

**`cd`** Change directory. Used in the context of `cd Desktop/MyFolder` it will take you to "My Folder"

**`cd ..`** Moves you up a level in your folder structure. 

**`cd ~`** Takes you to your home directory. If you get to a scary place this is very useful more getting out.

**`exit`** Techinically how you should close the terminal... clicking the x works too but its not recommended.

**`Ctrl + C`** When you write an infinite loop and need to get out.

<br>
<br>

Ok, so you have the command line open and you want to initialize a repository for a project folder that you already have on your computer. 

1. `cd` into the folder where all of your code exists. In your command prompt the last thing it prints should be the name of the folder you want to make a repo for. 
2. Check where you are using `pwd`
3. Check again where you are using `pwd`
4. Type `git init` and Enter
5. 


## On to the next [lesson](https://github.com/NowacekLab/Welcome/blob/master/lesson4.md)! (Or go [back a lesson!](https://github.com/NowacekLab/Welcome/blob/master/lesson2.md))
