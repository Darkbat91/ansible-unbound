[![Build Status](https://travis-ci.org/Darkbat91/ansible-unbound.svg?branch=v1)](https://travis-ci.org/Darkbat91/ansible-unbound)

# Unbound Installer for Ansible
Configures a simple secure [unbound](https://www.nlnetlabs.nl/projects/unbound/about/) server for DNS resolution and caching

## Defaults
By default it package is installed to the default location. with the below features.

- [Cloudflare](https://1.1.1.1/) and [Quad9](https://www.quad9.net/) as upstream resolvers
- [Yoyo Block List](http://pgl.yoyo.org/adservers/serverlist.php) as the default ad block list

## Changelog
The [changelog](./CHANGELOG.md) is stored externally