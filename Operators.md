# Operators

## Arithmetic Operators

The following operators are very similar to math: they calculate two numbers and result as a number.

|          | Math  | Python |
| -------- | ----- | ------ |
| add      | a + b | a + b  |
| minus    | a - b | a - b  |
| multiply | a × b | a * b  |
| divide   | a ÷ b | a / b  |
| power    | a^b^  | a ** b |

For example:

```python
print (3+2)     #You will get 5
print (10/4)    #You will get 2.5

a = 30-5
print (a)       #You will get 25
print (a/2)     #You will get 12.5
```

`+` can also used to combine two string, for example `print ("Hello" + " World!")` will give you `Hello World!`.

## Comparison Operators

There are some operators used to compare two values, they result as a Boolean value.

| Operator | Example  | Meaning                            |
| -------- | -------- | ---------------------------------- |
| ==       | `a == b` | If a and b are same                |
| !=       | `a != b` | If a and b are not same            |
| >        | `a > b`  | If a is greater than b             |
| >=       | `a >= b` | If a is greater than or equal to b |
| <        | `a < b`  | If a is less than b                |
| <=       | `a <= b` | If a is less than or equal to b    |

For example:

```python
print (1 == 2)  #False
print (1 != 2)  #True
print (1 > 2)   #False

a = 10
b = 20
print (a < b)   #True
result = a < b
print (result)  #True
```

Comparison operators can also used between strings:

```python
print ("test" == "test")#True
print ("b" > "a")       #True, because in alphabet, b is before a, so b is greater than a
print ("abc" < "abd")   #True
```

...also used in Booleans:

```Python
print (False == False)  #True
a = 2 > 3
print (a != True)       #True
```

## Logical Operators

Logical Operators are operators for Boolean values.

| Operator | Example   | Meaning                            |
| -------- | --------- | ---------------------------------- |
| and      | `a and b` | If a and b are all true            |
| or       | `a or b`  | If at least one of a and b is true |
| not      | `not a`   | Reverse true/false                 |

For example:

```python
t = True
f = False
print (t and f)    #False
print (t and t)    #True

print (t or f)     #True
print (f or f)     #False

print (not f)      #True
print (not t)      #False
```

## Operators Precedence

1. `**`
2. `*`, `/`
3. `+`, `-`
4. `<=`, `<`, `>`, `>=`
5. `==`, `!=`
6. `not`, `or`, `and`

You don't need to remember all of this, when you are confused of precedence, just use brackets to tell python which part you want to calculate first:

```python
print (1 + 2 * 3)   #7
print ((1 + 2) * 3) #9
```

## Assign a Variable with an Operator

An important thing to know is `a = 10` doesn't mean "variable a equals to 10", but "give value 10 to variable a".

When you are assigning a variable for example `a = 2 + 3`, python calculates the right side of the equal sign first (the result is 5), then assign 5 to the variable.

This is very important when you are trying to add one number to a variable. For example if you want to add 2 to `a`, you can write `a = a + 2` (`a` is 5 before running this code). Python will calculate right side first (`a + 2`), the result is 7, then python will assign 7 to `a`.