# DoltHub

Dolt is the first and only SQL database that you can fork, clone, branch, merge, push and pull just like a Git repository. Dolt is a version controlled database. Dolt is Git for Data.

Dolt implements the Git command line and associated operations on table rows instead of files. Data and schema are modified in the working set using SQL. When you want to permanently store a version of the working set, you make a commit. In SQL, dolt implements Git read operations (ie. diff, log) as system tables and write operations (ie. commit, merge) as stored procedures. Dolt produces cell-wise diffs and merges, making data debugging between versions tractable. Dolt is the only SQL database that has branches and merges.

## Guide:

URL: [DoltHub - Getting Started](https://docs.dolthub.com/introduction/getting-started/database)

## My first DoltHub repo:

URL: [angelodeath/a-dolt-ery](https://www.dolthub.com/repositories/angelodeath/a-dolt-ery)

## Install dolt cli:

### Windows:

```pwsh
> scoop install dolt
```

### MacOS:

```zsh
brew install dolt
```

### linux

```bash
nix-env
```
