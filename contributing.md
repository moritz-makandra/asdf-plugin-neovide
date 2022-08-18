# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test neovide https://github.com/moritz-makandra/asdf-neovide.git "neovide --version"
```

Tests are automatically run in GitHub Actions on push and PR.
