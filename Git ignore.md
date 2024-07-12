> # Git sees every file in your working copy as one of three things:

- tracked   - a file which has been previously staged or committed

- untracked - a file which has not been staged or committed

- ignored    - a file which Git has been explicitly told to ignore

Ignored files are tracked in a special file named .gitignore that is checked in at the root of your repository. There is no explicit git ignore command: instead the .gitignore file must be edited and committed by hand when you have new files that you wish to ignore. .gitignore files contain patterns that are matched against file names in your repository to determine whether or not they should be ignored.

