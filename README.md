# couchdb module for puppet

This module manages couchdb on Linux (RedHat/Debian) distros.

Pluginsync needs to be enabled for this module to function properly.
Read more about pluginsync in our [docs](http://docs.puppetlabs.com/guides/plugins_in_modules.html#enabling-pluginsync)

## Description

This module installs couchdb

## Usage

### couchdb
Installs the couchdb package.

    class { 'couchdb': }

