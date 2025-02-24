# Pushover CLI

A command line interface for [Pushover](https://pushover.net) notifications. This project is not written, maintained, or supported by Superblock (the creators of Pushover), and is not an official tool.

## Installation

```shell
wget -P /usr/local/bin https://oaklab.hu/crys/pushover-cli/-/raw/develop/pushover && chmod +x /usr/local/bin/pushover
```

## Usage

Run `pushover --help` for usage instructions.

### Configuration

This option allows you to set a global user key and application API token. This can be overridden on a per-use basis by specifying the `--user` and `--token` options.

```shell
pushover --config
```

### Upgrade

This option will upgrade to the latest release version.

```shell
pushover --upgrade
```
