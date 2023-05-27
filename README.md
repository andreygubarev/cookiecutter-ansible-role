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
molecule init scenario default --driver-name molecule-qemu --verifier-name testinfra
```

## Environment

Template has `Makefile` with targets for managing environment. To see all available targets run:
```sh
make help
```

Create virtual environment:
```sh
make virtualenv
```

# Reference

- [Cookiecutter](https://cookiecutter.readthedocs.io/en/stable/) - Templating library for creating boilerplate for projects.
