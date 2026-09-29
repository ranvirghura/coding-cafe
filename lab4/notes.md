Question 1
The --global flag tells Git to apply these user settings across all repositories on your system. If you omit it, the settings apply only to the current repository you are in, allowing repository-specific configurations.

Question 2
Running ls -a revealed the hidden .git directory, which standard ls hides. Inside .git is Git's internal database containing all repository configuration, object databases, commit history, and branch references.

Question 3
Git offers to track thousands of untracked files coming from the .venv directory. The entire contents of .venv/ were created automatically by Python for virtual environment dependencies and were not written manually.

Question 4
The entire .venv/ directory and its contents disappeared from the list of untracked files. In its place, .gitignore appears under the untracked files section.

Question 5
The .gitignore file should be committed to the repository rather than ignored. Committing it ensures everyone working on or cloning the project shares the same file-exclusion rules.

Question 6
README.md moved from "Untracked files" to "Changes to be committed". In the three-places model, running git add moved the file from the Working Directory to the Staging Area (Index).

Question 7
Git printed a summary indicating a successful commit on branch main (or master) along with the commit hash and message. It showed that 2 files changed (e.g., README.md and .gitignore) with their corresponding line insertions.

Question 8
The first seven characters are called the short commit hash (or SHA-1 hash). They serve as a unique identifier for that specific commit snapshot in the repository's history.
