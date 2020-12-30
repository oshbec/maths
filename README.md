# maths
Learning maths through programming


## Environment Setup

- [Install pyenv](https://github.com/pyenv/pyenv#installation):

```sh
brew install pyenv
```

- Install some Python build dependencies, as recommended by pyenv:

```sh
brew install readline xz
```

- Install latest stable Python w/ pyenv (a bit more complicated version shown because of Big Sur):

```sh
LDFLAGS="-L$(xcrun --show-sdk-path)/usr/lib" pyenv install 3.9.0
```

- Set my newly installed Python while inside this project directory:

```sh
cd maths
pyenv local 3.9.0
python --version
```

- [Install poetry](https://python-poetry.org/docs/#installation):

```sh
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```
