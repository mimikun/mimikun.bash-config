# 補完メモ

- doggo completions bash
- autohand completion bash
- acli completion bash
- codex completion bash
- kiro-cli completion bash
- goose completion bash
- taws completion bash
- `source <(pgit completion bash)`
- moon shell-completion --shell bash
- jg generate shell bash
- hyprmoncfg completion bash
- purple --completions bash
- sharedserver completion bash
- unifly completions bash
- tombi completion bash
- hk completion bash
- fnox completion bash
- pitchfork completion bash 
- `eval "$(fnox activate bash)"`
- `eval "$(pitchfork activate bash)"`
- pkl shell-completion bash
- rvpm completion bash

```shell
mkdir -p ~/.local/share/bash-completion/completions
# Local
moon shell-completion --shell bash >> ~/.local/share/bash-completion/completions/moon
deadbranch completions bash > ~/.local/share/bash-completion/completions/deadbranch
pitchfork completion bash > ~/.local/share/bash-completion/completions/pitchfork
usage --completions bash > ~/.local/share/bash-completion/completions/usage
aube completion bash   > ~/.local/share/bash-completion/completions/aube
jg generate shell bash > ~/.local/share/bash-completion/completions/jg
jg generate man -o ~/.local/share/man/man1/
rvpm completion bash > ~/.local/share/bash-completion/completions/rvpm

# Root
usage --completions bash > /etc/bash_completion.d/usage
aube completion bash   > /etc/bash_completion.d/aube
jg generate shell bash > /etc/bash_completion.d/jg.bash
```

