# iTerm2-Custom-Theme

## Instructions

### Open:

```bash
open -a TextEdit ~/.oh-my-zsh/themes/robbyrussell.zsh-theme
```

### Paste:

```zsh
PROMPT="%(?:%{$fg_bold[blue]%}%1{❯%} :%{$fg_bold[red]%}%1{➜%} ) %{$fg[blue]%}%c%{$reset_color%}"
PROMPT+=' $(git_prompt_info)'

ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg_bold[blue]%}(%{$fg[yellow]%}"
ZSH_THEME_GIT_PROMPT_SUFFIX="%{$reset_color%} "
ZSH_THEME_GIT_PROMPT_DIRTY="%{$fg[blue]%}) %{$fg[pink]%}%1{➔%}"
ZSH_THEME_GIT_PROMPT_CLEAN="%{$fg[blue]%})"
```
