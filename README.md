<div align="center">

# asdf-neovide [![Build](https://github.com/moritz-makandra/asdf-neovide/actions/workflows/build.yml/badge.svg)](https://github.com/moritz-makandra/asdf-neovide/actions/workflows/build.yml) [![Lint](https://github.com/moritz-makandra/asdf-neovide/actions/workflows/lint.yml/badge.svg)](https://github.com/moritz-makandra/asdf-neovide/actions/workflows/lint.yml)


[neovide](https://neovide.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add neovide
# or
asdf plugin add neovide https://github.com/moritz-makandra/asdf-neovide.git
```

neovide:

```shell
# Show all installable versions
asdf list-all neovide

# Install specific version
asdf install neovide latest

# Set a version globally (on your ~/.tool-versions file)
asdf global neovide latest

# Now neovide commands are available
neovide --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/moritz-makandra/asdf-neovide/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Moritz Kraus](https://github.com/moritz-makandra/)
