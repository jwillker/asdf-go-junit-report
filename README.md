<div align="center">

# asdf-go-junit-report [![Build](https://github.com/jwillker/asdf-go-junit-report/actions/workflows/build.yml/badge.svg)](https://github.com/jwillker/asdf-go-junit-report/actions/workflows/build.yml) [![Lint](https://github.com/jwillker/asdf-go-junit-report/actions/workflows/lint.yml/badge.svg)](https://github.com/jwillker/asdf-go-junit-report/actions/workflows/lint.yml)


[go-junit-report](https://github.com/jstemmer/go-junit-report) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add go-junit-report
# or
asdf plugin add go-junit-report https://github.com/jwillker/asdf-go-junit-report.git
```

go-junit-report:

```shell
# Show all installable versions
asdf list-all go-junit-report

# Install specific version
asdf install go-junit-report latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-junit-report latest

# Now go-junit-report commands are available
go-junit-report --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jwillker/asdf-go-junit-report/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jhonn W. Frazão](https://github.com/jwillker/)
