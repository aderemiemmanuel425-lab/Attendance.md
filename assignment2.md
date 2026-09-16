# Question 2.7
A) git log -n 3 → Displays only the most recent three commits in full detail
B) git log --oneline → Compact view showing 7-character commit hashes and one-line summaries
C) git log --oneline --graph --all → Graphical representation of branch forks, merges, and commit topology

# Section 3: Remote Repositories & GitHub Integration
  
## Part A: Conceptual Remote Mechanics

## Question 3.1

    B) The default shorthand alias name Git assigns to the remote repository URL.


## Question 3.2

    B) To align with modern inclusive terminology standards across the software industry.

## *Part B: Remote Commands & Syntax*

    1. git remote https://github.com/techcorp/student-portal.git
    2. git remote -v
    3. git push -u origin main 

## Question 3.4
    B) It links the local main branch with the remote origin/main branch, allowing future git push and git pull commands to be run without specifying the remote or branch name.

## Question 3.5
    1. It downloads the remote changes and updates origin/main, but does not modify your working directory or local main branch.
    2. git pull  git fetch + git merge 

## Question 3.6 
 1. git clone https://github.com/acme/backend.git
  2. yes 
   3. no