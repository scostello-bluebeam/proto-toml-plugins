# sdkman plugin

[sdkman](https://github.com/sdkman/sdkman-cli-native) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. To use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add sdkman "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/sdkman/plugin.toml" --global
proto install sdkman
```

### Per-project install

```shell
proto plugin add sdkman "source:https://raw.githubusercontent.com/scostello-bluebeam/proto-toml-plugins/main/sdkman/plugin.toml"
proto pin sdkman latest --resolve
```
