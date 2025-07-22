# Developer Helper

## Commands to Prepare This Description

Use the following commands to help you gather information for writing this pull request description:

### 1. Show list of staged changes (files added, modified, deleted):

```bash
git diff --cached --name-status
```

### 2. View detailed changes staged for commit:

```bash
git diff --cached
```

### 3. Get last commit message (if committing in chunks):

```bash
git log -1 --pretty=format:"%h %s"
```

### 4. List newly created folders (if restructuring):

```bash
git diff --cached --dirstat=files,0
```

### 5. Detect deleted or moved files:

```bash
git diff --cached --summary
```

### Optional: Summary for all unstaged and staged changes:

```bash
git status
```
