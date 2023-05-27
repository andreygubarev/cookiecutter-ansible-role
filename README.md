# Cookiecutter template for Ansible Role

Generate your project from the project template using latest version:

```sh
cookiecutter https://github.com/andreygubarev/cookiecutter-ansible-role.git
```

Generate your project from the project template using specific version:
```sh
cookiecutter https://github.com/andreygubarev/cookiecutter-ansible-role.git --checkout v0.1.0
```

Install desired `molecule` driver:
```sh
pip install molecule-qemu
```

Create scenario:
```sh
# molecule init scenario -r <role_name> -d <driver_name>
molecule init scenario default -d molecule-qemu
```

# Reference

- [Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/) - Templating library for creating boilerplate for projects.
