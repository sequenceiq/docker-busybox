This is a general Docker container image, to be able to use tools like:

- curl
- jq
- vim
- dig

## Usage

```
docker run -it --rm sequenceiq/busybox
```
## aliases

Aliases and PS1 promt is set from [sequenceiq bashrc](http://j.mp/seq-bashrc)
It provides the following aliases:
```
alias gl='git log --date=short --pretty=format:"%h %Cblue%ad%Creset %an %Cred%d %Cgreen%s%Creset" --graph'
alias gs='git status'
alias ll='ls -la'
alias digq='dig +search +nocmd +noall +answer +que'
alias digs='dig +search +short'
```
