<div align="center">

# asdf-localstack [![Build](https://github.com/Azulinho/asdf-localstack/actions/workflows/build.yml/badge.svg)](https://github.com/Azulinho/asdf-localstack/actions/workflows/build.yml) [![Lint](https://github.com/Azulinho/asdf-localstack/actions/workflows/lint.yml/badge.svg)](https://github.com/Azulinho/asdf-localstack/actions/workflows/lint.yml)

[localstack](https://github.com/python-localstack/localstack) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `python`: This needs python

# Install

Plugin:

```shell
asdf plugin add localstack
# or
asdf plugin add localstack https://github.com/Azulinho/asdf-localstack.git
```

localstack:

```shell
# Show all installable versions
asdf list-all localstack

# Install specific version
asdf install localstack latest

# Set a version globally (on your ~/.tool-versions file)
asdf global localstack latest

# Now localstack commands are available
localstack --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Azulinho/asdf-localstack/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Azul](https://github.com/Azulinho/)
