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

## FZF Fuzzy Command Line Search ##

This tool is very nice, and I use it's features constantly. The best feature for me is the enhanced `Ctrl+R` support. Type the start of the command and press `Ctrl+R` brings up selectable list of recent commands which you are able to search. It also does similar things when looking for files and switching directories. Check it out at <https://github.com/junegunn/fzf>

## Command line git viewer ##

`tig` is a great tool for seeing the commits, branches and diffs visually without leaving the command line. More here <https://github.com/jonas/tig>

## Another bunch of command line tips ##

This article is worth a look if you love using the command line <https://remysharp.com/2018/08/23/cli-improved>