# Changelog CLI

I have two use cases for this tool:

1. By default, the tool writes to `~/.changelog` - because my primary use case is to keep track of changes I make to various VPS'. I find that after some time has passed, I forget what's installed on it, or what tools are available. With this I can make quick notes to a global changelog.

2. A more vanilla use case: managing CHANGELOG in repos

## Install

```
❯ gem install changelog-cli
```

## Usage

```
❯ changelog -f CHANGELOG Added a CHANGELOG

[..]/CHANGELOG
  - Added a CHANGELOG

❯ changelog --where
CHANGELOG: ./CHANGELOG

❯ changelog --where -g
CHANGELOG: ~/.changelog
```

## FAQ

Open an issue to ask me a question

## License

MIT