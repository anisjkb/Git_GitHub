# Adding New Files to Your GitHub Repository

**<span style='color:red'>If you want to add all new and modified files, use following steps:</span>**

## Step 1: Check Git Initialization
If your local directory is not already a Git repository, initialize it using the `git init` command:

```bash
git init
```
## Step 2: Add Files to the Staging Area
Use the `git add` command to the staging area.

```bash
git add .
```

## Step 3: Commit the Changes
Commit the added files with a meaningful message using the `git commit` command:

```bash
git commit -m "Added all new files"
```

## Step 4: Push the Changes to GitHub
Push the committed changes to the GitHub repository using the `git push` command:

```bash
git push origin main
```

**<span style='color:green'>Now, your all new and modified files are successfully added to your GitHub repository!</span>**

# Adding only specific files to Your GitHub Repository

## Step 1: Navigate to Your Local Directory
Open your terminal or command prompt and move to the directory containing your local repository using the `cd` command.

```bash
cd "E:\Data Science\Git_GitHub"
```

## Step 2: Check Git Initialization
If your local directory is not already a Git repository, initialize it using the `git init` command:

```bash
git init
```

## Step 3: Add the Remote Repository (This steps is optional if "GitHub repository not exist")
Link your local repository to the existing GitHub repository using the `git remote add` command. If the remote repository is already added, skip this step.

```bash
git remote add origin https://github.com/anisjkb/Git_GitHub.git
```

## Step 4: Add Specific Files to the Staging Area
Use the `git add` command followed by the filenames to add only the new files to the staging area.

```bash
git add file1.txt file2.txt file3.txt
```
## Step 5: Commit the Changes
Commit the added files with a meaningful message using the `git commit` command:

```bash
git commit -m "Added three new files: file1.txt, file2.txt, file3.txt"
```

## Step 6: Push the Changes to GitHub
Push the committed changes to the GitHub repository using the `git push` command:

```bash
git push origin main
```
## Aditional (if faced following Error)

To https://github.com/anisjkb/Python-Django-RestAPI.git
 ! [rejected]        main -> main (fetch first)
error:failed to push some refs to 'https://github.com/anisjkb/Python-Django-RestAPI.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

```bash
git pull --rebase origin main
```
