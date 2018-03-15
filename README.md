# scripts

Stopgap scripts for bootstrapping a repository (until something like Docker is used)

The files in the [./script/](./script/) directory are copy/pasted into repositories.

# Use

- `./script/setup` Sets up the repository, installing any packages that are needed
- `LOG_LEVEL=trace ./script/setup` logs every command that is executed when setting up

# Languages

This section contains language-specific files that are needed to run code in this repository.

### Node

These are the files that are used to configure repositories that use https://nodejs.org

- `.node-version` : The version of node that should be used (installed via [nodenv](https://github.com/ekalinin/nodeenv))
- `package.json` : All libraries and any node scripts that are used
- `yarn.lock` : **(Optional)** Specific versions of libraries listed in `package.json` (installed via [yarn](https://yarnpkg.com))

### Python

These are the files that are used to configure repositories that use https://www.python.org

- `.python-version` : The version of python that should be used (installed via [pyenv](https://github.com/pyenv/pyenv))
- `requirements.txt` : All libraries that need to be installed
- `setup.py` : **(Optional)** alternative definition of libraries
