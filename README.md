# scripts

Stopgap scripts for bootstrapping a repository (until something like Docker is used)

The files in the [./script/](./script/) directory are copy/pasted into repositories.

# Use

- `./script/setup` Sets up the repository, installing any packages that are needed
- `LOG_LEVEL=trace ./script/setup` logs every command that is executed when setting up
