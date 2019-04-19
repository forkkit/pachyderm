## pachctl create branch

Create a new branch, or update an existing branch, on a repo.

### Synopsis


Create a new branch, or update an existing branch, on a repo, starting a commit on the branch will also create it, so there's often no need to call this.

```
pachctl create branch <repo>@<branch-or-commit>
```

### Options

```
      --head string           The head of the newly created branch.
  -p, --provenance []string   The provenance for the branch. format: <repo>@<branch-or-commit> (default [])
```

### Options inherited from parent commands

```
      --no-metrics           Don't report user metrics for this command
      --no-port-forwarding   Disable implicit port forwarding
  -v, --verbose              Output verbose logs
```
