1. --global saves the setting for my whole user account, in ~/.gitconfig, so it applies to every repository. Without it, Git uses --local and saves the setting only in the current repository’s .git/config.

2. The .git folder. It is hidden because its name starts with a dot. It holds the repository’s whole history and settings: the commits and stored file contents, the config, and the pointer to the current branch

3. About 2 items . Yes, .venv/ is not something I wrote. It is thousands of files of other people’s code.

4. .venv/ and __pycache__/  disappeared, because .gitignore tells Git to ignore them. .gitignore itself appeared as a new untracked file.

5. Committed. It is part of the project, and anyone who clones the repository should get the same ignore rules. If it were ignored, the rules would exist only on my machine.

6. It moved from Untracked files to Changes to be committed. In the three places (working directory, staging area, repository), git add moved it from the working directory into the staging area. It is not in the repository until I commit.

7.  3f3d5555ef4aa2baa42838e9defb3b73f9da58ae (HEAD -> master) and changed 4 files

8. They are the short commit hash (from SHA-1). Mine is "3f3d555 (HEAD -> master)".It is a unique ID for that commit, used to refer to it later, for example in git show, git checkout or git revert.
