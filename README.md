Ansible Role: uWSGI
=========

This role is for you to install **[uWSGI](https://github.com/unbit/uwsgi)** and some useful plugin

If you want this role to support more applications, you can [**submit Issues**](https://github.com/websoft9dev/role_uwsgi/issues/new/choose) for us.

## Requirements

Make sure these requirements need before the installation:

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x Ubuntu18.04 |
| Python version | Python2, Python3  |

## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before:

```
roles:
  - { role: role_common }
  - { role：role_uwsgi }
```


## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| uwsgi_version | "latest" | String | No |


## Example

```
  
```

## Resources

* [Documentation](https://support.websoft9.com/docs/uwsgi)
* [Deploy by Image](https://apps.websoft9.com/uwsgi)
* [Deploy by Script](https://github.com/websoft9/ansible-uwsgi)


## License

[LGPL-3.0](/License.md), Additional Terms: It is not allowed to publish free or paid image based on this repository in any Cloud platform's Marketplace.

Copyright (c) 2016-present, Websoft9

## FAQ

#### Is there uwsgi service?

Yes
