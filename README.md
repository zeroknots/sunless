<img align="right" width="150" height="150" top="100" src="./public/sunless.jpg">

# sunless ![license](https://img.shields.io/github/license/zeroknots/sunless?label=license)

Sunless is a Git submodules manager that simplifies the process of creating, adding, removing, and updating Git submodules. It's a shell script that acts as a wrapper around Git and the GitHub CLI, streamlining your submodule management tasks.

## Installation

1. Clone the Sunless repository:
```sh
git clone https://github.com/zeroknots/sunless
```


2. Add the Sunless script to your PATH

3. Source your .zshrc to apply the changes:
```sh
source ~/.zshrc
```

## Usage

Sunless has four main commands:

- `sunless create <repo_name>`: Creates a new GitHub repository and adds it as a Git submodule.
- `sunless add <repo_url>`: Adds an existing GitHub repository as a Git submodule.
- `sunless remove <repo_name>`: Removes a GitHub repository and its submodule.
- `sunless update`: Updates all Git submodules.


## Dependency: GitHub CLI

Sunless relies on the GitHub CLI to create and manage GitHub repositories. The GitHub CLI is an official command-line tool provided by GitHub that allows users to interact with GitHub features directly from the terminal. By using the GitHub CLI as a dependency, Sunless can automate various tasks, such as creating new repositories and obtaining repository information. Ensure that you have the GitHub CLI installed and configured for Sunless to work as expected.



