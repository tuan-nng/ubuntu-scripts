```
ls -rt | cat -n | while read n f; do mv "$f" "$n"; done
```

`ls -rt` to list by time in reverse order

`cat -n` to number all output lines

`read args` to read input
