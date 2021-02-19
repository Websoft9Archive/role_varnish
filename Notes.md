# Varnish Notes

Varnish is included in the EPEL repository, however due to incompatible syntax changes in newer versions of Varnish, only older versions are available.  

Varnish recommend that you install the latest version directly from: [packagecloud](https://packagecloud.io/varnishcache/varnish60lts/install#manual-rpm)

## Install 

```
# deb
curl -s https://packagecloud.io/install/repositories/varnishcache/varnish60/script.deb.sh | sudo bash

# rpm
curl -s https://packagecloud.io/install/repositories/varnishcache/varnish60/script.rpm.sh | sudo bash
```

## [Releases](http://varnish-cache.org/releases/index.html#releases)



| [6.5](http://varnish-cache.org/docs/6.5/)     | [Installation](http://varnish-cache.org/docs/6.5/installation/) | [Tutorial](http://varnish-cache.org/docs/6.5/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.5/users-guide/) | [Reference](http://varnish-cache.org/docs/6.5/reference/)   | Latest            |
| --------------------------------------------- | ------------------------------------------------------------ | --------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------- | ----------------- |
| [6.4](http://varnish-cache.org/docs/6.4/)     | [Installation](http://varnish-cache.org/docs/6.4/installation/) | [Tutorial](http://varnish-cache.org/docs/6.4/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.4/users-guide/) | [Reference](http://varnish-cache.org/docs/6.4/reference/)   | Previous          |
| [6.0](http://varnish-cache.org/docs/6.0/)     | [Installation](http://varnish-cache.org/docs/6.0/installation/) | [Tutorial](http://varnish-cache.org/docs/6.0/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.0/users-guide/) | [Reference](http://varnish-cache.org/docs/6.0/reference/)   | LTS               |
| [Trunk](http://varnish-cache.org/docs/trunk/) | [Installation](http://varnish-cache.org/docs/trunk/installation/) | [Tutorial](http://varnish-cache.org/docs/trunk/tutorial/) | [User-Guide](http://varnish-cache.org/docs/trunk/users-guide/) | [Reference](http://varnish-cache.org/docs/trunk/reference/) | Next              |
| [6.3](http://varnish-cache.org/docs/6.3/)     | [Installation](http://varnish-cache.org/docs/6.3/installation/) | [Tutorial](http://varnish-cache.org/docs/6.3/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.3/users-guide/) | [Reference](http://varnish-cache.org/docs/6.3/reference/)   | Deprecated        |
| [6.2](http://varnish-cache.org/docs/6.2/)     | [Installation](http://varnish-cache.org/docs/6.2/installation/) | [Tutorial](http://varnish-cache.org/docs/6.2/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.2/users-guide/) | [Reference](http://varnish-cache.org/docs/6.2/reference/)   | Deprecated        |
| [6.1](http://varnish-cache.org/docs/6.1/)     | [Installation](http://varnish-cache.org/docs/6.1/installation/) | [Tutorial](http://varnish-cache.org/docs/6.1/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/6.1/users-guide/) | [Reference](http://varnish-cache.org/docs/6.1/reference/)   | Deprecated        |
| [5.2](http://varnish-cache.org/docs/5.2/)     | [Installation](http://varnish-cache.org/docs/5.2/installation/) | [Tutorial](http://varnish-cache.org/docs/5.2/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/5.2/users-guide/) | [Reference](http://varnish-cache.org/docs/5.2/reference/)   | Late Middle Ages  |
| [5.1](http://varnish-cache.org/docs/5.1/)     | [Installation](http://varnish-cache.org/docs/5.1/installation/) | [Tutorial](http://varnish-cache.org/docs/5.1/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/5.1/users-guide/) | [Reference](http://varnish-cache.org/docs/5.1/reference/)   | High Middle Ages  |
| [5.0](http://varnish-cache.org/docs/5.0/)     | [Installation](http://varnish-cache.org/docs/5.0/installation/) | [Tutorial](http://varnish-cache.org/docs/5.0/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/5.0/users-guide/) | [Reference](http://varnish-cache.org/docs/5.0/reference/)   | Early Middle Ages |
| [4.1](http://varnish-cache.org/docs/4.1/)     | [Installation](http://varnish-cache.org/docs/4.1/installation/) | [Tutorial](http://varnish-cache.org/docs/4.1/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/4.1/users-guide/) | [Reference](http://varnish-cache.org/docs/4.1/reference/)   | Antiquity         |
| [4.0](http://varnish-cache.org/docs/4.0/)     | [Installation](http://varnish-cache.org/docs/4.0/installation/) | [Tutorial](http://varnish-cache.org/docs/4.0/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/4.0/users-guide/) | [Reference](http://varnish-cache.org/docs/4.0/reference/)   | Ancient History   |
| [3.0](http://varnish-cache.org/docs/3.0/)     | [Installation](http://varnish-cache.org/docs/3.0/installation/) | [Tutorial](http://varnish-cache.org/docs/3.0/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/3.0/users-guide/) | [Reference](http://varnish-cache.org/docs/3.0/reference/)   | Bronze Age        |
| [2.1](http://varnish-cache.org/docs/2.1/)     | [Installation](http://varnish-cache.org/docs/2.1/installation/) | [Tutorial](http://varnish-cache.org/docs/2.1/tutorial/)   | [User-Guide](http://varnish-cache.org/docs/2.1/users-guide/) | [Reference](http://varnish-cache.org/docs/2.1/reference/)   | Neolithic         |

6.0, 6.4, 6.5 are supported, other version are End-Of-Life and unsupported.

Recommend test 5.2, 6.0, 6.4, 6.5

## GUI

https://docs.varnish-software.com/varnish-administration-console/

