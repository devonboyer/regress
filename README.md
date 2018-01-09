# regress

### [`regress`](regress)

Regression testing tool for simple command line programs.

```bash
$ regress cat -o -n -p test
$ regress cat -o -n prefixes -p test
$ regress cat -o -n prefixes -p test1 test2
```

### [`progdiff`](progdiff)

Diff the output of a candidate program against a solution program. This tool is intended to be useful for checking solutions to assignments problems in university courses where a solution executable is often given.

```bash
$ progdiff ./foo-solution ./foo -o "-v"
```
