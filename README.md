# `gh stashes` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension for search your stash list and apply it.
![demo](https://user-images.githubusercontent.com/16704596/138599793-43f1496f-a7a9-4bb6-a2b6-f9fe446ff2ed.gif)

## Installation
```
gh extension install QWYNG/gh-stashes
```

## Usage
```
gh stashes
```

Displays an interactive stash selector that lists your stashes with preview that display   
```git show -p -G<QUERY> <SELECTED_STASH>```. The selected stash is applied.

This extension depends on [fzf](https://github.com/junegunn/fzf#readme) as a fuzzy finder. To install using Homebrew:
```
brew install fzf
```

