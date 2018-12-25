```shellsession
$ detree-cli < file.json
$ detree-cli < file.lamos
```

Exits with status `0` when the file is a valid `detree` decision tree.

Exits with status `1` and writes errors to `stderr` when the file is _not_ a valid `detree` decision tree.
