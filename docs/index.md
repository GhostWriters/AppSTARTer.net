# <!-- Home -->

[![AppSTARTer](https://raw.githubusercontent.com/GhostWriters/AppSTARTer.net/master/docs/img/logo.png)](https://appstarter.net)

The main goal of AppSTARTer is to make it quick and easy to get up and running with natively installed applications.

You may choose to rely on AppSTARTer for various changes to your application installs, or use it as a stepping stone and learn to do more advanced configurations and connecting applications together.

## Getting Started

### System Requirements

- You must be running a supported system (listed below).
- You must be logged in as a non-root user with sudo permissions.

### One Time Setup (required)

- APT Systems (Debian, Ubuntu, etc)

```bash
sudo apt-get install curl git
bash -c "$(curl -fsSL https://ghostwriters.github.io/AppSTARTer/main.sh)"
sudo reboot
```

- DNF Systems (Fedora)

Not currently supported, but planned to be in the future!

- YUM Systems (CentOS)

Not currently supported, but planned to be in the future!

## Running AppSTARTer

```bash
sudo apps
```

To run AppSTARTer use the command above. You should now see the main menu.

Currently, it is recommended to do Configuration > Select Apps as any other menu option just takes you through prompts to set variables that aren't currently used.

## Support

[![Discord chat](https://img.shields.io/discord/477959324183035936.svg?style=flat-square&color=607D8B&logo=discord)](https://discord.gg/YFyJpmH)

Click the chat badge to join us on Discord for support!

[[Feature Request](https://github.com/GhostWriters/AppSTARTer/issues/new?template=feature_request.md)] [[Bug Report](https://github.com/GhostWriters/AppSTARTer/issues/new?template=bug_report.md)]

## Contributors

[![GitHub contributors](https://img.shields.io/github/contributors/GhostWriters/AppSTARTer.svg?style=flat-square&color=607D8B)](https://github.com/GhostWriters/AppSTARTer/graphs/contributors)

This project exists thanks to all the people who contribute!

## Special Thanks

In addition to all those mentioned on [[DockSTARTer](https://dockstarter.com/)] we would also like to thank [[GhostWriters](https://github.com/GhostWriters/)] for being willing to partner and work with us to create AppSTARTer!
