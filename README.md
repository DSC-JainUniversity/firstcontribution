# first contribution
This repository is to help beginners make their first contribution. If you are looking to make your first contribution, you can start here.

If you don't have git on your machine, install it from this link - https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Step 1 - Fork this repository
Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

## Step 2 - Clone this repository
Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:

```
git clone "url you copied" 
```

## Step 3 - Create a branch
Change to the repository directory on your computer.

Now create a branch using the git checkout command:
```
git checkout -b your-new-branch-name
```

for example:
```
git checkout -b koushik-joshi
```

## Step 4 - Make and commit changes
Now open Contributors.md file in a text editor, add your name and branch name to it.

Add those changes to the branch you just created using the git add command:
```
git add Contributors.md
```

Now commit those changes using the git commit command:
```
git commit -m "Add <your-name> to Contributors list"
```
replacing ```<your-name>``` with your name.

## Step 5 - you are almost there!

Push your changes using the command git push:

```
git push origin <add-your-branch-name>
```

replacing ```<add-your-branch-name>``` with the name of the branch you created earlier.

## Submit your changes for a review

Go to your repository on GitHub, and click on the 'compare and pull request' button.

Next, submit the pull request.

We will review and merge your submissions and you will be notified via email.

## Congratulations! You just made your first contribution.
