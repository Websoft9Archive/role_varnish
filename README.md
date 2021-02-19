Ansible Role: Varnish
=========

This role is for you to install **[Varnish](http://varnish-cache.org/)**  

If you want this role to support more applications, you can [**submit Issues**](https://github.com/websoft9dev/role_varnish/issues/new/choose) for us.

## Requirements

Make sure these requirements need before the installation:

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu18.04 |
| Python version | Python2, Python2  |
| Runtime | No |

## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before:

```
roles:
  - { role: role_common }
  - { role: role_varnish }
```


## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| varnish_version |Varnish distribution version, e.g "6.0" | String | No |


## Example

```
varnish_version: "6.0"
  
```

## Resources

* [Documentation](https://support.websoft9.com/docs/varnish)
* [Deploy by Image](https://apps.websoft9.com/varnish)
* [Deploy by Script](https://github.com/websoft9/ansible-varnish)


## License

[LGPL-3.0](/License.md), Additional Terms: It is not allowed to publish free or paid image based on this repository in any Cloud platform's Marketplace.

Copyright (c) 2016-present, Websoft9

## FAQ

#### Which repository used for Varnish?

https://packagecloud.io/varnishcache