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

```shell
mkdir -p ~/.local/share/bash-completion/completions
moon shell-completion --shell bash >> ~/.local/share/bash-completion/completions/moon
jg generate shell bash > /etc/bash_completion.d/jg.bash
jg generate man -o ~/.local/share/man/man1/
```

