<p align="center">
  <img src="icons/icon.png" alt="Mockcat logo" width="128">
</p>

# Mockcat — downloads

The installers for [Mockcat](https://github.com/Haembina/mockcat), and nothing
else. There is no source code in this repository. Every file here is build
output, published by the release workflow in the source repository, which is
private.

## Getting it

The permanent link always resolves to the newest Windows installer:

```text
https://github.com/Haembina/mockcat-releases/releases/latest/download/Mockcat-x64-setup.exe
```

Each release also carries the installer under its version number, the Linux
packages, and `latest.json`: the version, the download URL and a detached
signature that an installed copy checks before it accepts an update.

## What the signature is, and is not

The `.sig` beside each installer is an updater signature. A running copy
verifies it against a public key compiled into the app, which proves an update
came from this pipeline and from nowhere else.

It is not an Authenticode certificate. It identifies no publisher to Windows,
so a fresh download shows an unknown-publisher warning.

## The app

Every mockup of every project in one window: browse them, see when and why each
was made, and answer an agent's question about them.
