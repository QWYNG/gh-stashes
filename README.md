# `gh stashes` GitHub CLI extension

[GitHub CLI](https://github.com/cli/cli) extension for search your stash list and apply it.

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

