# NetMeter tap

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
