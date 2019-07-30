# gitscripts
git-pushremote courtesy: https://github.com/shobhitpuri/git-refresh/blob/master/git-pushremote

## Setup Instructions
Run following (only prints; doesn't modify anything)
```
sh setup.sh
```

## Usage

### pushremote:
Force push: 
```
git pushremote -f
```

Push (1st time): 
```
git pushremote -u
```

Just push: 
```
git pushremote
```

### pullremote:
```
git pullremote
```

### pulltrack:
```
git pulltrack
```

### resethard:
```
git resethard
```

### newscratchbranch: 
(this can figure out track from current branch name; assumes track/orange or scratch/orange/cuties)
```
git newscratchbranch cuties
```

### newpullrequest:
opens a URL to create a new pull request to merge branch to the track (extracts track name from branch name)
```
git newpullrequest
```

### branchcommits:
commits on the scratch branch off the track (extracts track name from branch name)
```
git branchcommits
```

### removeuntracked
prints out command to clean untracked files
```
git removeuntracked
```

