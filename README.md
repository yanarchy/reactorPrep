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

##### Checking Status
```shell
git status
```

##### Version control---having git keep track of your changes
There are two steps: adding and committing. Think of it like an engagement and then a wedding.
Committing is like putting a flag or marker down on the coding road you are riding down.
It will allow you to 'return' to the state of your files at that point in time (if you want).
Later on, instead of doing undo (ctrl-z) a billion times, it will be easier for you to just turn back the clocks using git and go to a marker where your code was a-okay.

```shell
git add .
```
The . means all the files

```shell
git commit -m "[MESSAGE IN HERE]"
```

The ```-m``` is what we call a "flag". It's telling git that we want to attach a "commit message".

##### Making sure your remote repo on GitHub is up to date

```shell
git push origin master
```



