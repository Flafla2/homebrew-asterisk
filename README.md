# Homebrew Asterisk [Updated]

This repository is a fork of [leedm777/homebrew-asterisk][ast], with some trivial
modifications made to make the formula work on the latest version of homebrew.

## Installation

First you need to make sure that Homebrew's `sbin` exists and is included in your `PATH`:
    
    sudo mkdir -p /usr/local/sbin
    echo 'export PATH="/usr/local/sbin:$PATH"' >> ~/.bash_profile
    souce ~/.bash_profile

See the [original documentation][ast] for details on the brew install.  The basic install process looks like:

    brew tap flafla2/homebrew-asterisk
    brew install asterisk

All dependencies etc should be handled entirely by Homebrew.

If any other issues crop up over the years in this install process please send a PR my way
and I will do my best to integrate it.

 [ast]: https://github.com/leedm777/homebrew-asterisk