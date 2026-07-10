# Komga Flake with Desktop Launcher

This Nix flake installs Komga and provides:

* A wrapper script that starts Komga in the background
* A desktop launcher
* A custom application icon

## Build

Make sure Nix flakes are enabled, then run:

```bash
nix build
```

The build output will be available through the `result` symlink.

## Usage

Launch Komga from your application menu.

The launcher starts the Komga server and opens the following address in your browser:

```text
http://localhost:25600
```

## Included Components

* Komga version 1.21.3
* Java 17 runtime
* Desktop launcher
* Custom application icon
