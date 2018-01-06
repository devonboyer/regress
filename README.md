# regress

### [`regress`](regress)

Regression testing tool for simple command line programs.

```bash
$ regress cat -o -n -p test
$ regress cat -o -n prefixes -p test
$ regress cat -o -n prefixes -p test1 test2
```

### [`harness`](harness)

Test harness tool for testing the output of a candidate program against a solution program. 

```bash
$ harness ./foo-solution ./foo -o "-v"
```
