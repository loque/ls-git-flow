# ls-git-flow

Simple git flow

<!-- TODO: improve description -->

## Install

1. Download latest version of `lsgit`:

   ```bash
   sudo curl -L "https://github.com/loque/ls-git-flow/blob/main/lsgit" -o /usr/local/bin/lsgit
   # FIXME:
   sudo curl -L "https://github.com/loque/ls-git-flow/releases/download/v0.1.0-beta/lsgit" -o /usr/local/bin/lsgit
   ```

2. Apply executable permissions to the binary:
   <!-- TODO: is this necessary? -->
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

Bring changes from the default branch to the current one.

> Soon: If the current branch is a subfeature, changes will be merged from default to the feature and THEN to the subfeature.

```bash
lsgit update
```

<!-- TODO: explain commands in depth -->
<!-- TODO: add options -->

## Rename `master` branch to `main`

https://www.git-tower.com/learn/git/faq/git-rename-master-to-main
