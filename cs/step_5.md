## Použití pip

Na Raspberry Pi jsou nainstalovány dvě verze `pip`:

1. `pip` pro instalaci modulů Pythonu 2
2. `pip3` pro moduly Pythonu 3

Za normálních okolností bys měl používat pouze Python 3 a tedy `pip3`.

- Moduly můžeš nainstalovat pomocí příkazu `pip3 install`. Pokud si budeš chtít stáhnout například modul `guizero`, zadej toto do okna terminálu:

      ```bash
      sudo pip3 install guizero
      ```

![pi pip instalace](images/pi_pip_install.gif)

### Další příkazy pip

Existuje komplexní dokumentace pro pip na [pip.pypa.io](https://pip.pypa.io) — zde je několik užitečných příkazů:

- Upgrade již nainstalovaného modulu:

```bash
sudo pip3 install --upgrade jméno_modulu 
```

- Odinstalování modulu:

```bash
sudo pip3 uninstall name_of_module
```

- Seznam všech nainstalovaných modulů:

```bash
sudo pip3 list
```
