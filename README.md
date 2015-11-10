# snmp
PHP Class for net-snmp commands

Requirements
------------

Requires: net-snmp-utils

For RedHat/CentOS 6, 7

```shell
[root@centos ~]# yum install net-snmp-utils
```

Installation with Composer
--------------------------

```shell
$ composer require nelisys/snmp
```

Usage
-----

Example php file.

```php
// test-snmp.php
require 'vendor/autoload.php';

use Nelisys\Snmp;

```

Test run php file.

```shell
$ php test-snmp.php
```
