## What is pip?

If you have used Python before, you may have used code similar to these examples:

```python
from time import sleep
```

...or perhaps...

```python
import random
```

In the examples above, you are using code from a **module** written by somebody else. The modules in the examples above are called `time` and `random` and are included by default when you install Python.

However, lots of other code modules exist, and you might want to use some of their functions in your Python programs. For example, if you want to manipulate images you might want to use `PIL`, you could make games with `pygame` or craft GUIs with `guizero`. However, if you try to use these modules without installing them, they won't work:

![PIL not working](images/pil-doesnt-work.png)

This is where you need **pip**. You can use pip to install Python modules on your computer so that you can use them in your programs. You have probably seen instructions for installing Python modules in guides on the Raspberry Pi website and on other websites. 

A Raspberry Pi with the standard Raspbian distribution will have **pip** already installed.

