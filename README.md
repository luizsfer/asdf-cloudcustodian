<div align="center">

# asdf-cloudcustodian [![Build](https://github.com/luizsfer/asdf-cloudcustodian/actions/workflows/build.yml/badge.svg)](https://github.com/luizsfer/asdf-cloudcustodian/actions/workflows/build.yml) [![Lint](https://github.com/luizsfer/asdf-cloudcustodian/actions/workflows/lint.yml/badge.svg)](https://github.com/luizsfer/asdf-cloudcustodian/actions/workflows/lint.yml)

[cloudcustodian](https://github.com/luizsfer/asdf-cloudcustodian) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [asdf-cloudcustodian  ](#asdf-cloudcustodian--)
- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add cloudcustodian
# or
asdf plugin add cloudcustodian https://github.com/luizsfer/asdf-cloudcustodian.git
```

cloudcustodian:

```shell
# Show all installable versions
asdf list-all cloudcustodian

# Install specific version
asdf install cloudcustodian latest

# Set a version globally (on your ~/.tool-versions file)
asdf global cloudcustodian latest

# Now cloudcustodian commands are available
custodian --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/luizsfer/asdf-cloudcustodian/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Luiz Ferreira](https://github.com/luizsfer/)
