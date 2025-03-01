# git-utils

Git utility scripts

## Script

### Print branch list in long format

**Command**

```sh
git ll [-a|-d|-n]
```

**Options**

-   -a (default)  
    Print all branches
-   -d  
    Print only branches with a description
-   -n  
    Print only branches without a description

### Set branch description

**Command**

```sh
git set desc ${branch name} ${description}
```

**Example**

```sh
git set desc develop "For development environment"
```

**Options**

-   Current branch name `"."`  
    Using `"."` refers to the current branch.

> git set desc . "description"
