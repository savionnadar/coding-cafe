* **Question 1:** Using `--global` applies the name and email settings to all Git repositories on the machine. If left out, the configuration applies only to the current local repository.

* **Question 2:** The hidden `.git` folder appeared. Inside it are Git's internal metadata, configuration files, objects, logs, and tracking data required by the version control system.

* **Question 3:** There is no hard limit on the number of files and folders Git offers to track, but large repositories start to slow down. The `.venv/` folder contains thousands of files that were not written by me.

* **Question 4:** The `.venv/` directory disappeared from the untracked files list.

* **Question 5:** Yes, `.gitignore` should be committed. It ensures that the ignore rules are shared across all the cloned copies of the repository.

* **Question 6:** `README.md` moved from "Untracked files" to "Changes to be committed", it moved from the Working Directory to the Staging Area.

* **Question 7:** Git printed the commit summary showing the branch name, commit hash, commit message, and file status. It reported that **5 files changed**.

* **Question 8:** They are called a **short commit hash**. They serve as a unique identifier for that specific commit in the repository history.

* **Question 9:** The four steps of the loop are **Make changes**, **Check status** (`git status`), **Stage files** (`git add`), and **Commit to repository** (`git commit -m "..."`).

* **Question 10:** `README.md` is a standard filename and location that platforms like GitHub automatically show on the main repository page. It serves as the project's primary front page to explain what the repository contains.

* **Question 11:** `gh auth login` authenticates the GitHub user account via web login and saves a secure credential token locally on the system.

* **Question 12:** The `README.md` file in the root folder is displayed. GitHub automatically detects and formats this file on the front page to present the project details.

* **Question 13:** No, running `git push` does not change the local status in any way. It simply uploads your local commits to update the remote repository on GitHub so both match.

* **Question 14:** A private repository exists on GitHub, but access is restricted to you and invited collaborators. If a repository does not exist at all, no code or history has been uploaded to GitHub.
