# DevOps-V1

This repository was created using the following steps:

## 1. Create a local repository
-> Open the terminal and navigate to the directory where you want to place the repository.

-> Initialize a new git repository by doing:
```
git  init
```

## 2. Create a remote repository

-> Go to github (or the a platform of your choice where you want to host the repository).

-> Create a remote repository and follow the steps provided in the interface.

-> Remember to check the "ADD A LICENSE" option to add license to the repository.

## 3. Link remote repository to the local repository

-> Copy the remote repository url and in the remote repository do this:
```
git remote add origin <copied url>
```

## 4. Create a README.md file

-> In the local directory, create a README.md file and insert the following information to it. This is the file used to document information about the current repository.

## 5. Add, commit and push changes

-> Add the changes you have made in adding the README.nd file in the local repository by typing the following command in your terminal.
```
git add .
```
-> Commit the changes by typing:
```
 git commit
 ```

 A text editor will appear, type the heading and descriptions of the changes you have made in the current commit.

 -> Push the changes to the remote repository with the command:
```
 git push -u origin main
```
 This pushes the changes made to the remote main branch.
