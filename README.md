# Git Release

Git plugin script to checkout release branch, merge master, commit and push server release, and checkout master again all in one command.

### Prerequisites

Intended for use on a linux system with bash. Not tested on windows.

### Installing

Copy git-release file to your bin folder and make sure it is executable.


Open the terminal in the directory you want to use,
and run the command `git release`. This will run the following git commands in order:

`git checkout release`
`git merge master`
`git push server release`
`git checkout master`

## Authors

* **Joe Rothrock** - *Initial work* - [akmjoe](https://github.com/akmjoe)

## License

This project is licensed under the GPL License - see the [LICENSE.md](LICENSE.md) file for details

