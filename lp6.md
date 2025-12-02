# Lab Program 6: Revision Selection and Interactive Staging

**Scenario:**
Demonstrate the ability to navigate through Git history using various reference methods (hashes, logs, ancestry) and utilize the interactive staging menu to manage file updates with precision.

**Task List:**

1.  **Repository Setup & History Creation:**
    Initialize a repository, create a `readme.txt` file, and commit it. 
    Create a new branch named **testing**, add a new file (e.g., `testers.txt`), commit it, and then merge the testing branch back into the master branch to establish a commit history [cite: 243-249, 257-265, 278-279].

2.  **Revision Selection (Hashes & Branches):**
    Demonstrate how to view a specific commit using its full or short **SHA-1 hash**.
    Also, demonstrate how to view a commit by referencing a **Branch name** instead of a hash number [cite: 238-239, 287, 321].

4.  **Reflogs:**
    Display the local reference logs (Reflogs) to track the recent movement of the HEAD pointer. 
    Use a specific log entry (e.g., `HEAD@{2}`) to view a past state of the repository[cite: 240, 327, 334].

5.  **Ancestry References:**
    Demonstrate how to reference the parent of a commit using the **Caret (^)** or **Tilde (~)** symbols (e.g., showing the parent of the current HEAD) to navigate backwards in history [cite: 241, 363-364, 370].

6.  **Interactive Staging (Add Untracked):**
    Create multiple new files (e.g., `CONTRIBUTING.md` and `TESTERS.md`). Enter the **Interactive Staging** mode (`git add -i`).
    Use the menu options to select and **Add** these untracked files to the staging area [cite: 235, 422-431].

7.  **Interactive Revert:**
    While still in (or re-entering) the interactive mode, use the menu options to **Revert** (unstage) the files you just added, moving them back to the untracked state [cite: 396, 438-465].

8.  **Patching (Hunk Selection):**
    Modify a file with changes. 
    Use the interactive **Patch** mode to selectively stage specific parts (hunks) of the file [cite: 398, 493-505].
