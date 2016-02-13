##drunomics.php##
[![Build Status](https://travis-ci.org/drunomics/ansible-role-php.svg?branch=master)](https://travis-ci.org/drunomics/ansible-role-php)
Ansible role that installs php. Optionally with xdebug, xhprof.

Distribution: Ubuntu (tested on 14.04)

Supported PHP versions:

- PHP 5.5
- PHP 5.6
- PHP 7.0

## Requirements
None.

## Dependencies
None.

## Supported variables
The PHP version may be configured via the `php_version` variable; e.g.:

```
php_version: 5.5
#php_version: 5.6
#php_version: 7.0
```

For further variables, please check the documented variables defaults/main.yml.


(c) 2016 drunomics GmbH. /  MIT License