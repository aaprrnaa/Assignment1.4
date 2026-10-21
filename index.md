Step-by-Step Instructions
Step 1: Install Git & Verify Installation
What to do: Install Git if you haven't already and verify it works.

How to do it:

Download and install Git from git-scm.com.

Open your terminal and run the following command to verify:

Bash
git --version
Step 2: Configure Your Git Username and Email
What to do: Tell Git who you are so your commits are tagged with your name and email.

How to do it: Run these commands in your terminal (replace with your own name and email):

Bash
git config --global user.name "Your Full Name"
git config --global user.email "your.email@example.com"
Step 3: Initialize the Repository
What to do: Open your project folder (web-development-practice from previous assignments) in the terminal and turn it into a Git repository.

How to do it:

Bash
cd path/to/web-development-practice
git init
Step 4: Make 3 Meaningful Commits
To fulfill the requirement of making at least 3 distinct commits, you will make incremental changes to your project.

Commit 1: Create the initial HTML file

Create a file named index.html (if you haven't already) and add a basic heading.

Run the status and staging commands:

Bash
git status
git add index.html
git commit -m "chore: add initial index.html file"
Commit 2: Add a style sheet

Create a file named style.css and add some simple styling (e.g., body background color).

Run the status and staging commands:

Bash
git status
git add style.css
git commit -m "style: add base stylesheet and basic styles"
Commit 3: Add a JavaScript file or update content

Create a file named script.js with a simple console.log("Hello Git"); or update index.html with a paragraph.

Run the status and staging commands:

Bash
git status
git add .
git commit -m "feat: add JavaScript file for interactivity"
Step 5: View Your Commit History
To see your history of three commits and prepare for your screenshot, run:

Bash
git log --oneline
(Or just git log to see full details).

📸 What to Submit
Based on your assignment guidelines, capture the following screenshots:

Repository Folder: A screenshot of your project folder showing the files (index.html, style.css, script.js).

Commit History: A screenshot of your terminal window showing the output of git log or git log --oneline confirming your 3 successful commits.