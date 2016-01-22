# reactorPrep

## About
Hi Class! These are instructions for the shell/Terminal comands we went over in class today.

## Instructions

### What's Terminal?? What's Shell? What is this??
[Wtf is Terminal](http://askubuntu.com/questions/38162/what-is-a-terminal-and-how-do-i-open-and-use-it)

Each line in your terminal will begin with your username and a $ (unless you specified in your shell settings to be something else).

For me, it shows up as ```yfan$```

### Terminal Commands We Have Learned Today

##### To  navigate through folders:


```shell
cd [NAME OF FILE]
```

Example:
```shell
cd Documents/More\ Files/
```

* If you have spaces in your file names, use a backslash before each space
* To go back one level (one folder): ```cd ..```
* To go back to your home directory: ```cd```  (Just that, nothing else)

##### To list all of the items in a folder:
```shell
ls
```

### Git Commands We Have Learned Today

##### What is the version?

```shell
git --version
```

###### Clone from an online repo:
```shell
git clone [url.git]
```

So, if I were to clone the [jQuery repo](https://github.com/jquery/jquery), I would go on their Github and copy the git link to their repository (https://github.com/jquery/jquery.git).
And then I would do: ```git clone https://github.com/jquery/jquery.git```

And congrats! You'll have made a local repo on your machine. We refer to the repo that we have on our computer as 'local' and the corresponding repo online (usually on GitHub) as 'remote'.

##### Checking Status
```shell
git status
```

##### Version control---having git keep track of your changes
There are two steps: adding and committing. Think of it like an engagement and then a wedding.
Committing is like putting a flag or marker down on the coding road you are riding down.
It will allow you to 'return' to the state of your files at that point in time (if you want).
Later on, instead of doing undo (ctrl-z) a billion times, it will be easier for you to just turn back the clocks using git and go to a marker where your code was a-okay.

After saving your files...

```shell
git add .
```
The . means all the files. git add-ing is like getting engaged. You haven't fully committed yet but you're pretty darn sure.

```shell
git commit -m "[MESSAGE IN HERE]"
```

The ```-m``` is what we call a "flag". It's telling git that we want to attach a "commit message".
This is committing! You have now put a flag in the ground to let git know that this was a somewhat notable marker in your work so far.

##### Making sure your remote repo on GitHub is up to date

```shell
git push origin master
```

##### To create a ```gh-pages``` branch (or any branch)

```shell
git checkout -b [NAME OF BRANCH]
```
The -b lets git know that you're creating a new branch. If you would like to create a GitHub page, name your branch gh-pages.

Now that you've created a new branch, you can do your adding and committing in that branch, too.
To make sure your remote repo is synced up with your current branch:

```shell
git push origin [NAME OF YOUR BRANCH]
```
So if I have a branch named gh-pages, I would go ```git push origin gh-pages```.

### OMG I want to know more!!!! Git is awesome!!!!
Here are a bunch of good links and tutorials:

* [CodeSchool's Git Tutorial](https://try.github.io/levels/1/challenges/1) - I haven't used this so I can't tell you much about it except that it's popular. There may be a paywall at some point.
* [Udemy's Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/) - This is pretty dry. It reads like an encyclopedia. I would use this as a reference if you're not satisfied with explanations given by these other links. Will require focused reading though. Boo.
* [Git Immersion](http://gitimmersion.com/) - Going through this was a mandatory part of my Hack Reactor pre-course work. It can be a bit frustrating.
* [Git - The Simple Guide](http://rogerdudler.github.io/git-guide/) - This is like the opposite of Udemy's tutorial. Big letters, quick summaries. However, doesn't dive deep into details.

