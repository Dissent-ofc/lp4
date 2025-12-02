# Lab Program 7: Git Cleaning and Stashing

**Scenario:**
Demonstrate the ability to temporarily shelf (stash) incomplete work to clear the working directory and subsequently restore it. Also, demonstrate how to permanently remove untracked and ignored files from a repository.

**Task List:**

1.  **Stash Repository Setup:**
    Initialize a new repository named `stashdemo`.
    Create a file named `readme.txt` with some initial content and perform a commit to establish the baseline [cite: 118-124].

3.  **Stashing Work (The Stack):**
    * Modify the `readme.txt` file (simulate "Work in Progress").
    * **Stash** this change to revert the directory to the clean state [cite: 131-141].
    * Modify the file again with *different* content.
    * **Stash** this second change as well (demonstrating that multiple stashes can be stacked) [cite: 146-147].

4.  **Managing the Stash:**
    * **List** all the stashed entries to view the stack history[cite: 153].
    * **Apply** a specific stash (e.g., the older one, not the most recent one) back to your working directory [cite: 158-160].
    * **Drop** (delete) a specific stash entry from the stack to clean up [cite: 161-162].

5.  **Clean Repository Setup:**
    Initialize a separate repository named `cleandemo` with a committed readme file.
    Create a `.gitignore` file configured to ignore files with a specific extension (e.g., `*.a`) and commit it [cite: 178-192].

6.  **Create "Junk" Files:**
    Create two types of temporary files in your directory:
    * A file that matches the pattern in your `.gitignore` (e.g., `sample.a`)[cite: 201].
    * An untracked directory (e.g., `Test`) containing an untracked text file[cite: 205].

7.  **Cleaning Operations:**
    * Perform a **Dry Run** clean to display which files *would* be deleted without actually removing them [cite: 172, 214-215].
    * Perform a **Force Clean** to delete the standard untracked files [cite: 174, 217-218].
    * Perform a clean operation that specifically targets and removes **untracked directories** [cite: 175, 220-221].
    * Perform a clean operation that removes **all** files, including those listed in the `.gitignore` file (Ignored files) [cite: 176, 223-224].
