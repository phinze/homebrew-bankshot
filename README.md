# homebrew-bankshot

This is a Homebrew tap for [bankshot](https://github.com/phinze/bankshot).

## What is bankshot?

Bankshot provides automatic SSH port forwarding and browser opening for remote development. It consists of:
- `bankshot` - CLI tool for managing port forwards and opening URLs
- `bankshotd` - Local daemon that handles requests from remote SSH sessions

## Installation

```bash
brew install phinze/bankshot/bankshot
```

## Usage

After installation, start the daemon:

```bash
brew services start phinze/bankshot/bankshot
```

For detailed documentation and usage instructions, please visit the [main bankshot repository](https://github.com/phinze/bankshot).

## Uninstallation

```bash
brew services stop phinze/bankshot/bankshot
brew uninstall phinze/bankshot/bankshot
```

## License

MIT License - See the [main repository](https://github.com/phinze/bankshot) for details.