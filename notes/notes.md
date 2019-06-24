# VIM shortcuts
```sh
Shift + A - go to the end of the current row (insert mode)

Shift + C - delete everything after the cursor (insert mode)

Shift + I - go to the first letter on the current row (insert mode)

Shift + G - go to the last row of data in the file

/Pod - find any instances of Pod in the file

e - jump to the end of the next word

w - jump to the start of the next word

:25 - go to the 25th row in the file
```

# aliases

```sh
export ns=default
alias k='kubectl -n $ns' # This helps when namespace in question doesn't have a friendly name
alias kdr= 'kubectl -n $ns -o yaml --dry-run'.  # run commands in dry run mode and generate yaml.

```
