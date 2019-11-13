# Usage of custom jsone-studios bash-git-prompt

Clone this repo to your home directory:

```sh
git clone https://github.com/jsone-studios/bash-git-prompt.git ~/.bash-git-prompt --depth=1
```

Add this code snippet to your `~/.bashrc`:
```
if [ -f "$HOME/.bash-git-prompt/gitprompt.sh" ]; then
    GIT_PROMPT_ONLY_IN_REPO=0
	GIT_PROMPT_THEME=jsone-studios
    source $HOME/.bash-git-prompt/gitprompt.sh
fi
```
