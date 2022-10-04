# environment

Create an exploit development environment from a base Linux installation.

## Tutorial

Update package source information.

```sh
sudo apt update
```

Install development packages.

```sh
sudo apt install build-essential curl gdb git python3 python3-dev python3-pip python3-venv vim
```

Create a Python virtual environment.

```sh
python3 -m venv venv
```

Activate virtual environment.

```sh
source venv/bin/activate
```

Install Python packages from PyPI via pip.

```sh
pip install pwntools ropper keystone-engine
```

Install GDB Enhanced Features (GEF).

```sh
bash -c "$(curl -fsSL https://gef.blah.cat/sh)"
```

