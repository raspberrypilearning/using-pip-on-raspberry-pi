## Using pip

There are two versions of `pip` installed on the Raspberry Pi:

1. `pip` for installing Python 2 modules
2. `pip3` for Python 3 modules

Under normal circumstances, you should only be using Python 3 and therefore `pip3`.

- You can install modules using the `pip3 install` command. For example, if you wanted to download the `guizero` module, you would type this into a terminal window:

      ```bash
      sudo pip3 install guizero
      ```

![pi pip install](images/pi_pip_install.gif)

### Other pip commands

There is comprehensive documentation for pip at [pip.pypa.io](https://pip.pypa.io) — here are a few useful commands:

- Upgrade an already installed module:

```bash
sudo pip3 install --upgrade name_of_module 
```

- Uninstall a module:

```bash
sudo pip3 uninstall name_of_module
```

- List all installed modules:

```bash
sudo pip3 list
```
