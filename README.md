# Ansible Role: PHPStorm

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-phpstorm.svg)](https://travis-ci.org/tschifftner/ansible-role-phpstorm)

Installs PHPStorm on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    phpstorm_download_url: "https://download.jetbrains.com/webide/PhpStorm-{{ phpstorm_version }}.tar.gz"

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.phpstorm }

## Supported OS

Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
2.1              | Yes              | Yes             | Yes

## License

MIT / BSD

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)