# Pathway Documentation

This repository contains the latex source and figures for all of the Pathway application documentation.

## Contributing

You should follow these steps in order to contribute to the documentation.
1. Clone the repo to your machine with `git clone https://github.com/pathway-team/docs`.
2. Create a new branch named as follows `<section_or_doctitle>_<yourgithubusername>`
3. If you are creating a new document, then create a folder named after that document
    * keep the source for this doc in it's folder
4. Use a latex editor/ide to modify the source file, I personally use neovim and pandoc
    * there are easier tools to use though
    * [TeXstudio](https://www.texstudio.org)
    * [A big list of latex editors](https://tex.stackexchange.com/questions/339/latex-editors-ides)
5. Commit your changes as follows:
    * `git status` - to see what has changed.
    * `git add .` - to add all changes or `git add <file_name[s]>` - to add specific changes.
    * `git commit -m "commit message"` - to commit your added changes locally.
    * `git push origin <your_branch_name NOT MASTER!` - push your changes to the remote copy of your branch.
6. When your changes are ready, make a pull request on the github repository.

### New to git, check out this little [cheatsheet](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)

