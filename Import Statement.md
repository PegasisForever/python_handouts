# Import Statement

Import statement allows you to use code that in different files or written by others.

## Use Multiple Files

Put all your code in one file is bad for maintenance and hard to navigate between code. Put your code in to multiple files can make your work easier.

Just for demonstration, let's create two files, one called `main.py` and another called `functions.py`. Then put the following code to those files:

```python
#code in functions.py
def greet(name):
    print("Hello, " + name + "!")
```

```python
#code in main.py
import functions             #import <fileName>
functions.greet("Pegasis")   #fileName.functionName()
```

Then run `main.py`, you will see `Hello, Pegasis!` been printed out.

If you think use `fileName.functionName()` to invoke functions in other files is annoying, use another way to import it:

```python
#code in main.py
from functions import *
greet("Pegasis")
```

But this way is not encouraged because you may have conflicts. (for example a function you import have the same name with a function in your code)

## Use Modules

You can also import from others code using same syntax. For example you can import numpy for scientific math calculation, import pygame for making games and import tkinter for creating GUI (which we will learn later).

Next: *Object-Oriented (Basic Terms)*

