# Lab Program 2: Working with Branching and Merging

**Scenario:**
Configure secure access to a remote server and demonstrate the management of parallel development lines (branches) that result in a code conflict.

**Task List:**

1.  **Security Setup (SSH):**
    Generate an SSH public key on your local computer using the RSA algorithm. [cite_start]Add this generated key to your GitHub (or GitLab) account settings to enable secure, password-less communication [cite: 591-592, 612-621].

2.  **Repository Initialization:**
    Create a project folder, initialize the Git repository, and add a `README.md` file with some initial content. [cite_start]Perform a "First Commit" to establish the master branch history [cite: 599-604].

3.  **First Branch Operations:**
    Create a new branch named **Testing**. [cite_start]Switch to this branch, create a file named `TESTERS.md` (or modify the `README.md` file), and perform a commit to record these changes [cite: 593, 624-633].

4.  **Second Branch Operations:**
    Create a second, separate branch named **Bugfix**. [cite_start]Switch to this branch, create a file named `Bugfix.md` (or modify the `README.md` file), and perform a commit to record these changes [cite: 594, 637-641].

5.  **Simulate Merge Conflict:**
    Return to the master branch. Attempt to merge **both** the `Testing` branch and the `Bugfix` branch into master. [cite_start]Ensure that both branches have modified the same lines in the same file to trigger a **Merge Conflict** [cite: 595, 660-664].

6.  **Conflict Resolution:**
    Open the conflicted file, manually resolve the differences (choose which code to keep), and remove the conflict markers. [cite_start]Finalize the merge by performing a commit to ensure the master branch is clean and updated [cite: 595-596, 665-671].
