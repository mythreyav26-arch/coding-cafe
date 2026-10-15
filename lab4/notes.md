1. --global saves the setting for my whole user account, in ~/.gitconfig, so it applies to every repository. Without it, Git uses --local and saves the setting only in the current repository’s .git/config.

2. The .git folder. It is hidden because its name starts with a dot. It holds the repository’s whole history and settings: the commits and stored file contents, the config, and the pointer to the current branch

3. About 2 items . Yes, .venv/ is not something I wrote. It is thousands of files of other people’s code.

4. .venv/ and __pycache__/  disappeared, because .gitignore tells Git to ignore them. .gitignore itself appeared as a new untracked file.

5. Committed. It is part of the project, and anyone who clones the repository should get the same ignore rules. If it were ignored, the rules would exist only on my machine.

6. It moved from Untracked files to Changes to be committed. In the three places (working directory, staging area, repository), git add moved it from the working directory into the staging area. It is not in the repository until I commit.

7.  3f3d5555ef4aa2baa42838e9defb3b73f9da58ae (HEAD -> master) and changed 4 files

8. They are the short commit hash (from SHA-1). Mine is "3f3d555 (HEAD -> master)".It is a unique ID for that commit, used to refer to it later, for example in git show, git checkout or git revert.

9. The four steps of the loop are: edit a file, check it with git status, stage the change with git add, and commit it with git commit -m "message". I did this loop twice, once for my first commit and once for lab4/notes.md

10. The file is called README.md and sits in the repository’s top folder because it is the first thing anyone sees when they open the project. GitHub looks for a file with that name in the root and automatically displays it on the front page, rendered as formatted text. A name like notes.md would not be shown there, so visitors would not get the project’s introduction.

11. gh auth login signed me in through the browser and saved an access token on my computer. It also set Git to use that token, so Git does not ask for a password when I push.

12. gh auth login signed me in through the browser and saved an access token on my computer. It also set Git to use that token, so Git does not ask for a password when I push.

13. No. Pushing only copies my commits to GitHub, and the hashes and history are the same. The only change is a label like origin/main next to my latest commit.

14. A private repository still exists on GitHub's servers, but only I and the people I invite can see it. A repository that does not exist on GitHub has no copy online at all, only on my laptop.