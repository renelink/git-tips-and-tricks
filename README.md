# GIT Commit Hooks Distribution

This project shows how git hooks can be distributed and used per repository.

Just place the hooks you need in the `hooks` folder.

After you checked out this repository you can enable the hooks by setting the `core.hooksPath` to

    git config core.hooksPath './hooks'

Git will now execute the hooks from the repository. In my example it will output

![Example output
](git-commit-hook.png)

