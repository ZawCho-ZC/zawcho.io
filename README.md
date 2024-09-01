## Step 1: Create a New Repository on GitHub

1. Go to GitHub: Log in to my GitHub account.
2. Create a New Repository:
   - Enter a repository name - zawcho.io
   - Choose the visibility (public).


## Step 2: Clone the Repository to My Local Machine

1. Copy the Repository URL: git@github.com:ZawCho-ZC/zawcho.io.git.
2. Open Terminal: the directory where I want to clone the repository.
3. Clone the Repository:
   git clone git@github.com:ZawCho-ZC/zawcho.io.git


## Step 3: Configure Git with My Name and Email

1. Set My Name:
   git config --global user.name "Zaw Cho"
   
2. Set My Email:
   git config --global user.email "zawcho.zc1@gmail.com"

   
## Step 4: Create and Manage Branches

### a. Create a New Branch

1. Navigate to the Repository:
   cd zawcho.io
   
2. Create and Checkout a New Branch:
   git checkout -b feature/new-feature

   
### b. Create a New Text File

1. Create `feature.txt`: Use a text editor to create a file named `feature.txt` and add some text,"This is a new feature."


### c. Commit Changes

1. Add the File:
   git add feature.txt
   
2. Commit the Changes:
   git commit -m "Add feature.txt with new feature"

   
### d. Push the Branch to the Remote Repository

1. Push the Branch:
   git push origin feature/new-feature

   
### e. Create a Pull Request

1. Go to GitHub: Navigate to my repository.
2. Create a Pull Request: Click on "Compare & pull request" for the `feature/new-feature` branch.
3. Submit the Pull Request: Add a title and description, then click "Create pull request."


### f. Review and Make Changes

1. Review: Check the changes in the pull request.
2. Make Changes: If needed, make changes in my local branch, commit, and push again.


### g. Merge the Pull Request

1. Merge: Once satisfied, click "Merge pull request" and confirm.


## Step 5: Collaborate with a Classmate

### a. Invite a Collaborator (Yin Yin Min Naing)


### b. Ask Collaborator to Clone the Repository


### c. Assign a Task

1. Assign a Task: Communicate with my collaborator to add a new file or modify an existing one.


### d. Review and Approve Changes

1. Review Pull Request: Once my collaborator submits a pull request, review the changes.
2. Approve and Merge: If everything looks good, merge the pull request.
