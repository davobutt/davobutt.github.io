---
author: Dave Butt
title: Command Line Tips
---

## Finding what's eating your port ##

To see which process has opened a particular port do (for port 9229):
```
lsof -i TCP:9229
```
For more information pass the PID to `ps -p <PID>`

## Github's *hub* command line git extension ##

This tools wraps and augments the existing `git` command line, to make it easier to work with github. Get it at <https://github.com/github/hub>


```
# Clone a repo from your organisation
git clone holidayextras/the-works

# Open the current repo in your browser on github
git browse

# Pull Requests
git pr list
git pr checkout <PR NUMBER>

# Open github compare page
git compare
```

Plus loads of other goodness.. see <https://hub.github.com/hub.1.html> for all the commands