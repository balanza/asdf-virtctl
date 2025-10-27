<div align="center">

# asdf-virtctl [![Build](https://github.com/balanza/asdf-virtctl/actions/workflows/build.yml/badge.svg)](https://github.com/balanza/asdf-virtctl/actions/workflows/build.yml) [![Lint](https://github.com/balanza/asdf-virtctl/actions/workflows/lint.yml/badge.svg)](https://github.com/balanza/asdf-virtctl/actions/workflows/lint.yml)

[virtctl](https://github.com/kubevirt/kubevirt/tree/main/pkg/virtctl) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Install

Plugin:

```shell
asdf plugin add virtctl
# or
asdf plugin add virtctl https://github.com/balanza/asdf-virtctl.git
```

virtctl:

```shell
# Show all installable versions
asdf list-all virtctl

# Install specific version
asdf install virtctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global virtctl latest

# Now virtctl commands are available
virtctl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/balanza/asdf-virtctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Emanuele De Cupis](https://github.com/balanza/)
