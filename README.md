structuredfun-linux
===================

Client-side media server for Linux in a box

Install
-------
StructuredFun requires PHP 5.3 or later, but PHP 5.5 or later is recommended for performance reasons.

This repo contains a submodule so either checkout recursively or don't forget to pull down the submodule (/structured/htdocs).

```git clone --recursive https://github.com/lightenna/structuredfun-linux.git```

Configure
---------
You can run the server locally using PHP's embedded web server:

```php -S localhost:8097```

Then view the app in a browser:

```firefox http://localhost:8097/```

Alternatively an example vhost is provided to running in production.

Virtual host
------------
An example virtual host is provided in /structured/conf/vhosts/sturcturefun.conf.  This will need customising for your environment.

App-specific setup
------------------
Further information on how to configure settings and shares is in the submodule's README (/structured/htdocs/README.md) file.
