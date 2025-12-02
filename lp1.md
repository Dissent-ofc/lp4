# Lab Program 1: Working with 3-Stage GIT Pipeline

**Scenario:**
Initialize a git repository called "Project" and perform the following operations to demonstrate the standard Git workflow, log viewing, and undo capabilities.

**Task List:**

1.  **Repository Setup:**
    [cite_start]Create a new directory named "Project" and initialize it as a Git repository [cite: 16-19].

2.  **Perform Commits:**
    [cite_start]Create three different text files (e.g., `file1.txt`, `file2.txt`, `file3.txt`) and commit them separately with meaningful messages to create a history of three distinct commits [cite: 20-29].

3.  **Log Formatting:**
    [cite_start]Display the commit log history, but format the output to show only the "Commit Hash," "Author Name," and "Author Date" for each entry [cite: 10, 30-31].

4.  **Ignore Specific Files:**
    [cite_start]Create a standard ignore file (`.gitignore`) that instructs Git to exclude any files that start with a vowel (`[aeiou]*`) from being tracked [cite: 11, 32-36].

5.  **Examine Differences:**
    Demonstrate the `diff` command by performing the following comparisons:
    * [cite_start]Compare the files currently in the **Staging Area** against the **Last Commit**[cite: 46, 58].
    * [cite_start]Compare the difference between two specific commits (e.g., the Second commit versus the First commit)[cite: 47, 70].
    * [cite_start]Show the changes made in a specific commit relative to its parent (using the caret `^` notation)[cite: 48, 81].

6.  **Amend a Commit:**
    Assume you forgot to include a file or made a mistake in the last commit message. [cite_start]Demonstrate how to append a new file to the **current** (most recent) commit without creating a new separate commit hash [cite: 13, 89-95].

7.  **Unstaging Files:**
    Simulate a scenario where you accidentally staged two files but intended to commit only one. [cite_start]Demonstrate how to revert a specific file from the **Staged** area back to the **Unstaged** area while keeping the file changes in the directory [cite: 14, 98-102].
