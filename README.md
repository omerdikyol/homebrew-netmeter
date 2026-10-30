<h1 align="center">NetMeter tap</h1>

<p align="center">
  <img alt="Homebrew: cask" src="https://img.shields.io/badge/Homebrew-cask-FBB040">
  <img alt="platform: macOS" src="https://img.shields.io/badge/platform-macOS-lightgrey">
  <img alt="license: MIT OR Apache-2.0" src="https://img.shields.io/badge/license-MIT%20OR%20Apache--2.0-green">
</p>

Homebrew casks for [NetMeter](https://github.com/omerdikyol/netmeter), a network
usage monitor for the macOS menu bar.

```sh
brew tap omerdikyol/netmeter
brew trust omerdikyol/netmeter
brew install --cask netmeter
```

The cask here is the one that installs. Its source lives in the NetMeter
repository under `packaging/homebrew/netmeter.rb`.

## Cask source

[Casks/netmeter.rb](Casks/netmeter.rb) declares the release version, download checksum, application install, and cleanup paths. For screenshots, supported macOS versions, and source builds, see [the NetMeter repository](https://github.com/omerdikyol/netmeter).
