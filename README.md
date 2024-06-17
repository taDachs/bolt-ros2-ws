# Human Centred Robotics Workspace

This is a workspace for the human centred robotics lecture. It contains a devcontainer config, which
can be used with VSCode or the [devcontainer cli](https://github.com/devcontainers/cli). For VSCode
you need the devcontainer extension. It also contains a repo file, which can be used with
[vcstool](https://github.com/dirk-thomas/vcstool) to quickly pull all needed repositories.

## Using the devcontainer cli

```bash
devcontainer up --workspace-folder ./
devcontainer exec --workspace-folder ./ zsh
```
