======================
My NixOS configuration
======================

Setup
-----

Create `/etc/nixos/hardware-configuration.nix` elsewhere.

Symlink to appropriate locations:

export GIT_REPO_DIR=...

cd /etc/nixos/ && ln -s "$GIT_REPO_DIR/configuration.nix"
