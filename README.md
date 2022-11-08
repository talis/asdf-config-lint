<div align="center">

# asdf-config-lint [![Build](https://github.com/talis/asdf-config-lint/actions/workflows/build.yml/badge.svg)](https://github.com/talis/asdf-config-lint/actions/workflows/build.yml) [![Lint](https://github.com/talis/asdf-config-lint/actions/workflows/lint.yml/badge.svg)](https://github.com/talis/asdf-config-lint/actions/workflows/lint.yml)

[config-lint](https://github.com/stelligent/config-lint) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

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
asdf plugin add config-lint
# or
asdf plugin add config-lint https://github.com/talis/asdf-config-lint.git
```

config-lint:

```shell
# Show all installable versions
asdf list-all config-lint

# Install specific version
asdf install config-lint latest

# Set a version globally (on your ~/.tool-versions file)
asdf global config-lint latest

# Now config-lint commands are available
config-lint --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/talis/asdf-config-lint/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Talis](https://github.com/talis/)
