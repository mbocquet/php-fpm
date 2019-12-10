# php-fpm

Ansible role to install and configure php-fpm (PHP FastCGI Process Manager).

## Requirements

None.

## Role Variables

Many. See defaults/main.yml

## Dependencies

None.

## Install this roles as submodule of an existing GIT repository

`git submodule add https://git.sekoya.org/mb/php-fpm.git roles/php-fpm`

## Example Playbook

    - hosts: servers
      roles:
         - php-fpm


    - hosts: servers
      roles:
         - { role: php-fpm, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
