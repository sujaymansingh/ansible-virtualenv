# ansible-virtualenv

Use this to create a python virtualenv at the given directory, and install a
requirements from the given file.

```
  - role: sujaymansingh2.virtualenv
    virtualenv_path: /opt/envs/someapp
    virtualenv_requirements_file: /opt/someapp/requirements.pip
    virtualenv_user: vagrant
    virtualenv_group: vagrant
```

If you want to have system site packages, use

```
    virtualenv_site_packages: "--system-site-packages"
```
