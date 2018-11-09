# xdebug
OSX / Unix
---
```
$ git clone https://github.com/xdebug/xdebug.git
$ cd xdebug
$ ./remake.sh
```
Windows
---
Has executable files for your php version. 
Run `$ php -v` to find it out. 
https://xdebug.org/download.php

Additional configuration:
---
Find out php.ini location:
`$ php --ini`

Add to PHP.INI file:
```
zend_extension="xdebug.so"
xdebug.remote_enable=1
```

Reload php.ini [depending on environment / restart wamp / xamp]:
```sudo service apache2 restart```

Running `$ php -v` should yield something like below if the installation was successful:
```
PHP 7.2.10 (cli) (built: Sep 15 2018 02:28:03) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
    with Zend OPcache v7.2.10, Copyright (c) 1999-2018, by Zend Technologies
    with Xdebug v2.7.0beta2-dev, Copyright (c) 2002-2018, by Derick Rethans
```

Chrome
---
Install https://chrome.google.com/webstore/detail/xdebug-helper/eadndfjplgieldjbigjakmdgkmoaaaoc

PHPStorm
---
### Server setup:
![server setup](https://i.imgur.com/TA3k0zH.png)

### Debugger setup:
![debug setup](https://i.imgur.com/0mxw1E3.png)

