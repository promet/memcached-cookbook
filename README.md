memcached cookbook
------------------

This cookbook provides a basic memcached install and config.

Requirements
------------
* [vagrant](http://downloads.vagrantup.com/) >= 1.2.0
* [berkshelf](http://berkshelf.com/) >= 2.0.0
* [vagrant-berkshelf plugin](https://github.com/RiotGames/vagrant-berkshelf) >= 1.3.3

Usage
-----

In your Vagrantfile, customize these attributes:

````
default['memcached']['logfile']           = "/var/log/memcached.log"
default['memcached']['memory']            = "128"
default['memcached']['port']              = "11211"
default['memcached']['user']              = "memcache"
default['memcached']['listen_ip']         = "127.0.0.1"
default['memcached']['connection_limit']  = "1024"
````

Attributes
----------

No additional attributes yet.

Recipes
-------

No additional recipes yet.

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
License: None.  Do as you wish.
Authors: gregpalmier
