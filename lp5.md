# Lab Program 5: Git Branching, Merging, Rebasing, and Conflict Resolution

**Scenario:**
Demonstrate the difference between standard merging and rebasing, resolve a merge conflict, and show the effects of different reset modes on the repository history.

**Task List:**

1.  **Repository Initialization:**
    Initialize a new Git repository named `git-demo` and create a sample file (e.g., `demo.txt`). [cite_start]Perform an "Initial commit" to start the history [cite: 732-737].

2.  **Fast-Forward Merge:**
    Create a new branch called **feature**. Switch to it and append a new line to your sample file. Commit the change. [cite_start]Switch back to the main branch and merge the feature branch to demonstrate a **Fast-forward** merge (where the history line does not fork) [cite: 739-746, 750-753].

3.  **Create Diverging History (Conflict Setup):**
    * [cite_start]On the **main** branch, append a specific line to the sample file and commit it [cite: 759-761].
    * [cite_start]Switch to the **feature** branch, append a *different* line to the same file, and commit it [cite: 763-767].
    * (This ensures that both branches have "moved forward" separately).

4.  **Merge Conflict and Resolution:**
    Attempt to merge the **feature** branch into the **main** branch. Observe that Git halts due to a conflict. [cite_start]Open the file, manually resolve the conflict markers, and perform a commit to finalize the resolution [cite: 769-771, 780-784].

5.  **Rebase Demonstration:**
    Switch to the **feature** branch. [cite_start]Perform a **Rebase** operation of the feature branch onto the main branch to demonstrate how Git creates a linear history by replaying commits on top of the latest changes [cite: 789-791].

6.  **Reset Operations (Hard vs. Soft):**
    Demonstrate the ability to undo commits using the Reset command:
    * [cite_start]Perform a **Soft Reset** to the previous commit (demonstrate that changes are kept in the Staging Area) [cite: 812-813].
    * [cite_start]Perform a **Hard Reset** to the previous commit (demonstrate that all changes and uncommitted work are completely erased) [cite: 815-816].
