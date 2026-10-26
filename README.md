# Trifork Tally CLI Homebrew tap

Official Homebrew tap for installing and updating the Trifork Tally CLI on macOS.

The Tally CLI is developed and distributed by **Trifork A/S**.
Copyright © 2026 Trifork A/S. All rights reserved.

## Install

```bash
brew install trifork/tally-cli/tally-cli
```

The initial release supports Apple Silicon Macs running macOS 13 or newer.
After installation, authorized Tally users can run:

```bash
tally setup
```

## Update

```bash
brew update
brew upgrade tally-cli
```

## Uninstall

```bash
brew uninstall tally-cli
```

Uninstalling the formula does not delete Tally CLI configuration, Keychain
credentials, or a separately installed reminder schedule.

## License

The application and tap are provided under the restrictive
[Trifork Tally CLI Limited Use License](LICENSE). The license permits downloading,
installing, and using an unmodified copy solely with a Tally account for which the
user is authorized. It does not permit modification, redistribution, sublicensing,
sale, hosting, or provision to third parties.

Third-party dependencies remain subject to their respective licenses.
