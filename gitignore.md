# gitignore

**Term**: gitignore

**Definition**: A `.gitignore` file is a configuration file in Git, that instructs Git not to track certain files or directories in your project. This means that these files are not being tracked, uploaded or included in the repository when a commit is made. They could be system files, `.env` files that store passwords or API keys etc. (All files that are not relevant to the repository)

**Example**: If you're for example working on a Python-based machine learning project. You have local configuration files, logs, and a large dataset that is unnecessary for version control. In this scenario, you can include these files and directories in a `.gitignore` file, ensuring they don't get uploaded to your repository.

**Code Snippet**: Here is an example for a .gitignore file. You can add comments with #.

```plaintext
#
# .gitignore
#

# Ignore Sublime Text files.
*.sublime-workspace

# Ignore environment file
.env

# Ignore Python Cache directory
__pycache__

# Ignore data directory
/data/
```
