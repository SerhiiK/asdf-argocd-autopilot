<div align="center">

# asdf-argocd-autopilot [![Build](https://github.com/SerhiiK/asdf-argocd-autopilot/actions/workflows/build.yml/badge.svg)](https://github.com/SerhiiK/asdf-argocd-autopilot/actions/workflows/build.yml) [![Lint](https://github.com/SerhiiK/asdf-argocd-autopilot/actions/workflows/lint.yml/badge.svg)](https://github.com/SerhiiK/asdf-argocd-autopilot/actions/workflows/lint.yml)

[argocd-autopilot](https://argocd-autopilot.readthedocs.io/en/stable/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add argocd-autopilot
# or
asdf plugin add argocd-autopilot https://github.com/SerhiiK/asdf-argocd-autopilot.git
```

argocd-autopilot:

```shell
# Show all installable versions
asdf list-all argocd-autopilot

# Install specific version
asdf install argocd-autopilot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global argocd-autopilot latest

# Now argocd-autopilot commands are available
argocd-autopilot version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/SerhiiK/asdf-argocd-autopilot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Serhii Krupskyi](https://github.com/SerhiiK/)
