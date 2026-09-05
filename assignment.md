# Section 1 : Version Control Foundation & Core Architecture 

__part A :Conceptual MCQs__ 

**Question 1**
 1 B) Git is a distributed version control system running locally; GitHub is a cloud-hosted platform providing remote repository hosting and team collaboration tooling. 
 2 B) Every collaborator's local computer contains a complete clone of the repository, including its full historical timeline and branches.
 3B) A hidden directory named .git/ is created containing Git’s internal tracking databases, object stores, and configuration. 

 **part B : Architecture & Three Areas Analysis**

Question 1.4 (3 Points)
 
1. x)  git add — moves changes from the Working Directory into the Staging Area (Index).
2. [Y] = git commit — records the staged snapshot in the Git Repository.
3. Area: Git Repository (Local History) — committed files are recorded as Git objects and referenced by the commit's SHA-1/SHA-256 hash.

**Part C: True / False Conceptual Verification**

**Question 1.5**
1. True 
2. False 
3. True 


# Section 2: Installation, Configuration & The Daily Git Cycle

**Part A: Configuration & Setup**

**Question 2.1**

1. git config --global user.name "Jane Developer"
2. git config --global user.email "jane.dev@example.com"


**Question 2.2**

 B)  git config --list 

**Question 2.3**

B) Git commits will fail or be recorded with a generic fallback system username, preventing accurate attribution in
GitHub contribution graphs and audit trails.

**Part B: The Daily Git Operations Cycle**

**Question 2.4**

1. git status 
2. git add
3. git commit 
4. git log 

**Question 2.5**

Command A: git add index.html — stages only index.html (including its modifications, if any).

Command B: git add . — stages all eligible changes in the current directory and its subdirectories, rather than just one named file.

**Part C: Commit Message Conventions & Inspection**

**Question 2.6**

Reason 1: Descriptive messages make the commit history easy to understand, allowing developers to quickly identify what each change accomplished.

Reason 2: Imperative, specific messages improve collaboration and maintenance by making changes easier to review, troubleshoot, and understand later.
