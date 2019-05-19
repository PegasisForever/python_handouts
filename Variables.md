# Variables

## Variable Naming Rules

As I said in *Basic Terms*, you can use almost everything as your variable name, but you neet to follow those rules:

- Must start with a letter or an underscore
- The remainder of your variable name may consist of letters, numbers and underscores
- Names are case sensitive

![examp1e](Variables.assets/examp1e.png)

For example, those variable names are acceptable:

`example` `Example` `_example` `_example2`

And those are not acceptable:

`2example` `example!` 

## Assigning a Variable

Assign a variable means you are giving a value to a variable.

Here are some examples: (sentence after `#` is comment)

```python
variable1 = 25              #assign 25 (number type) to a variable called variable1
variable2 = "Hello World!"  #assign Hello World! (string type) to a variable called variable2
variable3 = False           #assign False (boolean type) to a variable called variable3
```

Also, you can assign a variable by another variable:

```python
a = 10    #assign 10 to a, easy to understand
b = a     #because a's value is 10, so this line is same as b = 10
```

## Test If it Works

Now we already assigned a value to a variable, but how can we actually comfirm it? Use `print()` function. Since we are not starting teaching function yet, the only thing you need to know is **put your variable name in the brackets, this function will show what’s in the variable in the shell**.

For example:

```python
var = 12345
print (var)
```

After running this, `12345` should shown in the shell.