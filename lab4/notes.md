* **Question 1:** Using `--global` applies the name and email settings to all Git repositories on your machine. If left out, the configuration applies only to the current local repository.


* **Question 2:** The hidden `.git` folder appeared. Inside it are Git's internal metadata, configuration files, objects, logs, and tracking data required by the version control system.


* **Question 3:** There is no hard limit on the number of files and folders Git offers to track, but large repositories start to slow down. The `.venv/` folder contains thousands of files that were not written by me.


* **Question 4:** The `.venv/` directory and compiled Python file entries (`__pycache__`, `*.pyc`) disappeared from the untracked files list.


* **Question 5:** Yes, `.gitignore` should be committed. It ensures that the ignore rules are shared across all the cloned copies of the repository.


* **Question 6:** `README.md` moved from "Untracked files" to "Changes to be committed", it moved from the Working Directory to the Staging Area.


* **Question 7:** Git printed the commit summary showing the branch name, commit hash, commit message, and file status. It reported that **5 files changed**.


* **Question 8:** They are called a **short commit hash**. They serve as a unique identifier for that specific commit in the repository history.