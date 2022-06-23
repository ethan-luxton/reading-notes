## Introduction to Git (Lab 03 Notes)

Git is an amazing way (and the industry standard way) of cloning, pushing, pulling and commiting changes to code. But, what are the changes made by clone, pull, push or commit?

* Clone:
    * "Cloning" are the commands used to get a version of a codebase from whatever source you are using. In most instances this source is GitHub!
    * This is most commonly achieved through these commands:

```console
git clone (arguments)
git init (arguments)
```
* Pull:
    * "Pulling" are the commands used to fetch from and integrate another repository on GitHub. Demonstrated by this command (This is used to update the local repository to the latest branch alongside the merge command):

```console
git pull (arguments)
git merge (arguments)
```

* Push:
    * "Pushing" are the commands used to push the changes made in the codebase to the main branch. Basically taking all the changes made locally and getting them ready to send back to GitHub. Demonstrated by this command:

```console
git push (arguments)
```

* Commit:
    * "Commiting" are the commands used to commit those changes before pushing them to GitHub. Demostrated by this command (with two arguments usually):

```console
git commit (arugument) (argument)
```


### Lastly...

Changes made locally must be added before commiting or pushing them to the main branch on GitHub. How is this achieved? The "add" command.

```console
git add (file)
git add . (the . represents all files)
```

To summarize, changes made to a GitHub repository locally must be (saved on the users local file) added to the git repository locally, commited to the repository and pushed to the GitHub repository before it shows up online. 

[Back to main page](README.md)