# ls-git-flow

Simple git flow

## Install

1. Download latest version of `lsgit`:

   ```bash
   sudo curl -L "https://github.com/loque/ls-git-flow/blob/main/lsgit" -o /usr/local/bin/lsgit
   ```

2. Apply executable permissions to the binary:
   ```bash
   sudo chmod +x /usr/local/bin/lsgit
   ```

## Commands

### start

Create and checkout to a new feature or subfeature branch.

```bash
lsgit start [BRANCH NAME]
```

### end

Merge the current branch to its parent branch and delete it.

```bash
lsgit end
```

### update

Bring changes from the default branch to the current one. If the current branch is a subfeature, changes will be merged from default to the feature and THEN to the subfeature.

```bash
lsgit update
```

## Rename `master` branch to `main`

https://www.git-tower.com/learn/git/faq/git-rename-master-to-main
