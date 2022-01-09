<div align="center">

# asdf-tab ![Build](https://github.com/barolab/asdf-tab/workflows/Build/badge.svg) ![Lint](https://github.com/barolab/asdf-tab/workflows/Lint/badge.svg)

[tab-rs](https://github.com/austinjones/tab-rs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `sha256sum`.

# Install

Plugin:

```shell
asdf plugin add tab
# or
asdf plugin add tab https://github.com/barolab/asdf-tab.git
```

tab:

```shell
# Show all installable versions
asdf list-all tab

# Install specific version
asdf install tab latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tab latest

# Now tab commands are available
tab --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/barolab/asdf-tab/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Romain Bailly](https://github.com/barolab/)

# Credits

This repository was heavily inspired from [asdf-exa](https://github.com/nyrst/asdf-exa)
