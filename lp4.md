# Lab Program 4: Working with Remote Repository

**Scenario:**
Demonstrate how to synchronize with a remote repository, pull the latest changes from a specific branch, and perform cleanup by deleting branches both locally and remotely.

**Task List:**

1.  **Repository Setup:**
    Initialize a local repository named `pushfetch` and add a `readme.txt` file with some content. [cite_start]Perform a first commit and **Push** this local repository to a new empty project on GitHub [cite: 537-543, 552-554].

2.  **Remote Branch Creation:**
    Go to the GitHub webpage for your repository and manually create a new branch named **Testing**. (This simulates a branch created by a collaborator) [cite_start][cite: 567].

3.  **Fetching Changes:**
    [cite_start]In your local terminal, update your repository's references to see the new remote branch without merging it into your current work (Demonstrate the **Fetch** operation)[cite: 535, 571].

4.  **Track Remote Branch:**
    [cite_start]Create and switch to a new local branch named **Testing** that tracks the `Testing` branch from the remote repository[cite: 534, 573].

5.  **Local Cleanup:**
    Switch back to the `main` branch. [cite_start]Delete the **Testing** branch from your local machine [cite: 534, 579-580].

6.  **Remote Cleanup:**
    [cite_start]From your local terminal, issue a command to **delete** the `Testing` branch on the remote GitHub server[cite: 534, 582].

7.  **Fetch vs. Pull:**
    (Verbal or Practical) [cite_start]Demonstrate or explain the difference between `git fetch` (downloading changes without merging) and `git pull` (downloading and updating immediately) [cite: 535, 561-564].
