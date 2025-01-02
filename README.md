# gh-branch-protector

GitHub CLI utility to protect GitHub branches.

## protect-branch script

The script assumes that you have a valid JSON file with the rules of your branch protection.
It must be named `config/protect-branch.json`.

```sh
Usage: protect-branch -o OWNER -r REPO -b BRANCH

Options:
  -o OWNER    GitHub owner (user or organization)
  -r REPO     Repository name
  -h          Show this help message
```

## TODO

[] -b BRANCH option to specify the name of the branch
[] Update an existing ruleset

