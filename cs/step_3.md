## Co je pip?

Pokud jste dříve používali Python, možná jste použili kód podobný tomuto:

```python
from time import sleep
```

Nebo možná toto:

```python
import random
```

In the examples above, you are importing a **module** in order to use code written by somebody else. The modules in the examples are called `time` and `random`, and are included by default when you install Python.

Lidé však napsali spoustu dalších modulů Pythonu a možná budeš chtít použít některé z jejich funkcí ve svých programech Python. For example, if you want to manipulate images you might want to use `PIL`, or you could make games with `pygame`, or craft GUIs with `guizero`. Pokud se však pokusíš použít tyto moduly bez jejich instalace, nebudou fungovat:

![PIL not working](images/pil-doesnt-work.png)

This is where **pip** comes in. To be able to use use external Python modules in your programs, you can use the pip tool to install them on your computer. (Pravděpodobně jsi již viděl pokyny pro instalaci modulů Pythonu s pip v průvodcích na webu Raspberry Pi a na jiných webech.)

A Raspberry Pi with the standard version of Raspbian will have pip already installed.
