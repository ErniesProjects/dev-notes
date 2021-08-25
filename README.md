# Git Basics

## CLONE

On your local machine (the rpi) clone this repository with:

```
cd /home/pi                # change to your home directory
git clone                  # clone the repository
cd FIXME                   # cd into the new directory
```

## ADD

Whenever you've created files, or made changes to existing files, you need to add those changes.  Some examples:

```
git add .                  # adds all files from the current directory (and subdirectories)
git add path/to/file       # add a specific new/modified file
```

## COMMIT

After you've added new files or changes, you have to *commit* those changes.  Important - this does not push your changes to github, this just records all the changes you've added with a single "commit message"

```
git commit -m 'some message'	# commit with an inline message
git commited					# this will open an editor for your message
```


## PUSH

Finally, push your changes to github with `git push`


## STATUS

At any time, run `git status` to see what files are changed, what needs to be commited, etc:

* in red means you have not added the changes
* in yellow-green means added but not commited


## PULL

If someone else has made changes, or you've made changes from another machine and want to pull those changes to your local code, use `git pull`

