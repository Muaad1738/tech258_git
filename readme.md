# Git 

## What is Version Control?

Version control is like an unlimited 'undo' button for your code. It lets you track changes, collaborate with others, and manage your projects effectively.

## What is Git?

Git is a popular version control system. It helps you keep track of changes you make to your code and allows you to save every version of your project.

## Basic Git Commands

- **git init**: Start tracking changes in a project.
- **git status**: Check the current status of your project.
- **git add**: Add changes to the next snapshot.
- **git commit**: Save your changes with a message.

## Additional Git Commands

- **git log**: View a history of your commits.
- **git diff**: See the differences between versions.

## .gitignore

**.gitignore** tells Git what files to ignore. You can use it to exclude temporary files or sensitive data from being tracked

## Distributed Version Control

![Central or decentralised](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190820174942/CVCS-vs-DVCS.png)

Centralised version control relies on a central server for version control, while decentralised version control allows developers to work independently and collaboratively without a central point of control. Decentralised version control allows more flexibility and scalability compared to centralised version control. 

## What is GitHub?

GitHub is an online platform that provides hosting for software projects. It has features like version control using Git and others like issue tracking, pull requests. This makes it a popular choice for developers to collaborate.

## Other Options/Competitors 

  

Some alternatives to GitHub include: 

  

- **GitLab**: Like GitHub, GitLab offers version control and collaboration features, but it is also self-hosted, this allows users more control over their data. 

  

- **Bitbucket**: Bitbucket provides Git and Mercurial version control systems. It is known for its integration with other Atlassian products like Jira and Confluence. 

## How to Link a Local Repository to a Remote Repository on GitHub

1. **Make a Remote Repository on GitHub:**
   - Go to GitHub and sign in to your account.
   - Select "New repository."
   - Create a new repository, giving it a name.

2. **Locate Your Project Directory:**
   - Open GitBash
   - Use the `cd` command to navigate to the directory where your local Git repository is located.

3. **Link Local Repository to Remote Repository:**
   - Initialise the local repository:
     ```
     git init
     ```
   - Add the remote repository URL as the origin:
     ```
     git remote add origin 
     ```
     Add the URL of the remote repository on GitHub. 

4 **Push Your Commits to the Remote Repository:**
   - Push your local commits to the remote repository:
     ```
     git push -u origin master
     ```
     This command pushes your changes from the local master branch to the origin remote repository. 





