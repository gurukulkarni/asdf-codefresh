<div align="center">

# asdf-codefresh ![Build](https://github.com/gurukulkarni/asdf-codefresh/workflows/Build/badge.svg) ![Lint](https://github.com/gurukulkarni/asdf-codefresh/workflows/Lint/badge.svg)

[codefresh](https://codefresh-io.github.io/cli) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add codefresh
# or
asdf plugin add https://github.com/gurukulkarni/asdf-codefresh.git
```

codefresh:

```shell
# Show all installable versions
asdf list-all codefresh

# Install specific version
asdf install codefresh latest

# Set a version globally (on your ~/.tool-versions file)
asdf global codefresh latest

# Now codefresh commands are available
codefresh version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/gurukulkarni/asdf-codefresh/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Guruprasad Kulkarni](https://github.com/gurukulkarni/)
