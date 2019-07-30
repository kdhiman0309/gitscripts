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
(this can figure out track from current branch name; assumes track/orange or scratch/orange/mandarin)
```
git newscratchbranch mandarin
```
