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
Does `git push -f origin <current_branch>`
```
git pushremote -f
```

Push (1st time): 
Does `git push -u origin <current_branch>`
```
git pushremote -u
```

Just push: 
Does `git push origin <current_branch>`
```
git pushremote
```

### pullremote:
Does `git pull origin <current_branch>`
```
git pullremote
```

### track:
Extracts track name from branch name. Assumes formats for branch: `scratch/trackname/some_name` and for track: `track/trackname`
```
git track
```

### resethard:
Hard resets current branch
Does `git reset --hard origin/<current_branch>`
```
git resethard
```

### pulltrack:
Does `git pull origin <track>`. Check `git track`
```
git pulltrack
```

### newscratchbranch: 
Create new scratch branch of format `scratch/trackname/some_name`. Uses `git track`
```
git newscratchbranch cuties
```

### newpullrequest:
opens a URL in browser to create a new pull request to merge current_branch into the track
Use `git track`
`<track> <- <current_branch>`
```
git newpullrequest
```

### branchcommits:
commits on the scratch branch off the track. Uses `git track`
```
git branchcommits
```

### removeuntracked
prints out command to clean untracked files
```
git removeuntracked
```

