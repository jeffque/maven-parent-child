To test property in `parent`:

```bash
mvn help:evaluate -Dexpression=lalala -q -DforceStdout -pl :parent
```

To test property in `child`:

```bash
mvn help:evaluate -Dexpression=lalala -q -DforceStdout -pl :child
````
