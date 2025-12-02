<div align="center">

# asdf-jwt-cli [![Build](https://github.com/dobesv/asdf-jwt-cli/actions/workflows/build.yml/badge.svg)](https://github.com/dobesv/asdf-jwt-cli/actions/workflows/build.yml) [![Lint](https://github.com/dobesv/asdf-jwt-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/dobesv/asdf-jwt-cli/actions/workflows/lint.yml)

[jwt-cli](https://github.com/mike-engel/jwt-cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add jwt-cli https://github.com/dobesv/asdf-jwt-cli-plugin.git
```

jwt-cli:

```shell
# Show all installable versions
asdf list-all jwt-cli

# Install specific version
asdf install jwt-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jwt-cli latest

# Now jwt-cli commands are available
jwt
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dobesv/asdf-jwt-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Dobes Vandermeer](https://github.com/dobesv/)
