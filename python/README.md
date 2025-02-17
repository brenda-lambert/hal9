# Hal9

Design Interactive Data Apps Without Web Dev

## Installation

```bash
$ pip install hal9
```

### Source

Validate Python 3.9 or newer is installed

```bash
python3 --version
```

Clone and build package as follows

```bash
git clone https://github.com/hal9ai/hal9 && cd hal9
pip3 install maturin
maturin build -m python/Cargo.toml -F pyo3 -b pyo3
pip3 install python/target/wheels/* --force-reinstall
````

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`hal9` was created by Anchit Sadana, Kevin Kuo and Javier Luraschi. It is licensed under the terms of the MIT license.

## Credits

`hal9` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
