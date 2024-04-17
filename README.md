# GitGlossary2024

This repository is a collaborative project created for the purpose of learning about Git commands and Git-related collaborative workflows. Each participant will contribute to our collaborative Git glossary by providing one entry to it. 

## Contribution Guidelines

### Initialization

- **Fork this Repository**: Begin by forking the repository to your own GitHub account.
- **Clone Your Fork**: Clone the forked repository to your local machine.

### Making Contributions

- **Create a New Branch**: Create a branch for your specific contribution. Name it after the git term you are explaining, e.g., `git branch add`.
- **Switch to New Branch**: Switch to your branch, e.g. `git switch add`.
- **Copy the Template**: You'll find a `template.md` in the directory. Copy this file and rename it according to the term you are documenting, e.g., `add.md`.
- **Edit the File**: Follow the format specified in `template.md` to fill out your term, definition, example, and code snippet.
- **Commit Your Changes**: Commit your changes with a clear message, e.g., "Add definition for <term>".
- **Push Your Changes**: Push your branch to your GitHub fork. Note if you are pushing a branch for the first, you need to use the --set-upstream flag, e.g., `git push --set-upstream origin add`. For follow-up pushes, you can simply use `git push`. 
- **Submit a Pull Request**: Go to your Githut fork, and make a pull request to the main repository for integration and review.

### Review Process and Merging

- Each pull request must be reviewed by at least one person.
- Reviewers should check for accuracy and clarity.
- Pull requests can be merged once they have been approved.
- In this simple setup, conflicts are unlikely, since everyone is working in a separate file. 
- However, should any merge conflict arise (e.g. if simultaneous edits are made to the README file), then try to resolve the conflict (either locally or on Github).
