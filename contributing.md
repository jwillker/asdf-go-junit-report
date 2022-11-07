# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test go-junit-report https://github.com/jwillker/asdf-go-junit-report.git "go-junit-report --help"
```

Tests are automatically run in GitHub Actions on push and PR.
