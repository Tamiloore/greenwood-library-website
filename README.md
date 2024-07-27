# Capstone Project -Greenwood-Library-Website
## Project Description:
As a part of development team tasked with enhancing the website for the "Greenwood Community Library." The website aims to be more engaging and informative for it's visitors. It currently includes basic sections which i wrote the html code: 
- Home
- About us 
- Events 
- Contact us 

My Team decides to add a "Book Reviews" Section and update the "Events" page to feature upcoming community event.

## Task:
I will simulate the roles of two contributors 

1. Morgan - focusing on adding the "*Book Reviews*" section 
2. Jamie - Updating the "*Events*" page with new community event 

## Step 1:
**Create a Github Repository**: Login into your Github account to create a repository,
- Add Repository name 
- Initialize this "repository with README file"
- Create a repo

![alt text](img/1_repo.png)
 
 ## Step 2:
 **Cloning(downlod) The Repo**: 
 - Click on Code 
 - Select SSH (if you've configured your SSH to Github, if not use HTTPS)
 - Copy the link by clicking on the copy icon

![alt text](img/2_copycode.png)

 ## Step 3:
 **Cloning(downlod) The Repo on your local Repo**: 
 - Open your gitbash 
 - Run  `git clone "paste the link copied"`

![alt text](img/2_gitclone.png)

## Step 4:
 **Open Vscode from your terminal**: 
 - Open your gitbash 
 - Run  `code .`

![alt text](img/3_vscode.png)

## Step 5:
 **Select the directory created**: 

![alt text](img/3_vscode1.png)

## Step 6:
 **Create The HTML files**: 
- Create html files and add your codes

![alt text](img/3_vscode2.png)
![alt text](img/image.png)

# Morgan's Contribution 

## Step 7:
 **Open The Cloned Repo**: 
 - `cd` into the directory 
 - `ls` to see the what is inside 

 ![alt text](img/4_cdintomain.png)

## Step 8:
 **Create a Branch**: 
 - Run `git checkout -b New_features/Add_book_review` to create and switch into a new branch
 
![alt text](img/5_cdintomain.png)

## Step 9:
 **Create a New HTML File**: 
 - Run `touch book_review.html` to create to a new file
 - You can also create it on Vscode and make your edit anyone you wish.
 - `ls` to view the created file

![alt text](img/6_cdintomain.png)

## Step 10:
 **Edit the New HTML File**: 
 - Run `vim touch book_review.html` to edit 
 - You can also  make your edit anyone you wish.

![alt text](img/7_cdintomain.png)

## Step 11:
 **Stage the Edited files**: 
 - Run `git status` to check if the status of the files
 - If it shows red, means it hasn't been added
 - Run `git add "name of the file"` to add the files 
 - Run `git status` to check again, if it's green means it has been succesfully staged 

![alt text](img/8_cdintomain.png)

## Step 12:
 **Commit files**: 
 - Run `git commit -m "message you want to pass"` 

![alt text](img/9_cdintomain.png)

## Step 13:
 **Push File**: 
 - Run `git push` 
 - You might get an error, don't panic 
 - Copy the suggested command and run it again 

![alt text](img/10_cdintomain.png)

## Step 14:
 **Compare & Pull Request**: 
 - Go back to your Github account
 - Click the Compare and pull request 

![alt text](img/11_cdintomain.png)

## Step 15:
 **Create a Pull Request**: 
 - Click on pull request
 - You can decide to Edit the Commit message and add descriptions 

![alt text](img/12_cdintomain.png)

# Jamie's Contribution
## Apply same process as Morgan's by starting from 
- Creating a new branch 
- Once you create new branch, you will have access to all the documents from the main branch 
- Vim to edit the *events.html* file
- Add edit with same command 
- Commit 
- Then Push
