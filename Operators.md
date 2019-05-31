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

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005860" width="100%" height="181px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

**Warning:** the result of the math operation with decimal number is not always 100% accurate, for example, `print (0.2+0.1)` will give you `0.30000000000000004`, not `0.3`.

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

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005871" width="100%" height="235px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Comparison operators can also used between strings:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005879" width="100%" height="145px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

...also used in Booleans:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005890" width="100%" height="127px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Logical Operators

Logical Operators are operators for Boolean values.

| Operator | Example   | Meaning                            |
| -------- | --------- | ---------------------------------- |
| and      | `a and b` | If a and b are all true            |
| or       | `a or b`  | If at least one of a and b is true |
| not      | `not a`   | Reverse true/false                 |

For example:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005899" width="100%" height="253px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Operators Precedence

1. `**`
2. `*`, `/`
3. `+`, `-`
4. `<=`, `<`, `>`, `>=`
5. `==`, `!=`
6. `not`, `or`, `and`

You don't need to remember all of this, when you are confused of precedence, just use brackets to tell python which part you want to calculate first:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005909" width="100%" height="109px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Assign a Variable with an Operator

An important thing to know is `a = 10` doesn't mean "variable a equals to 10", but "give value 10 to variable a".

When you are assigning a variable for example `a = 2 + 3`, python calculates the right side of the equal sign first (the result is 5), then assign 5 to the variable.

This is very important when you are trying to add one number to a variable. For example if you want to add 2 to `a`, you can write `a = a + 2` (`a` is 5 before running this code). Python will calculate right side first (`a + 2`), the result is 7, then python will assign 7 to `a`.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559119217" width="100%" height="156px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Example Code

Reading other's code is very important on your road of learning programming. Following are some lines of code and their output. Read, run and change the code, try to understand them.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005918" width="100%" height="91px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559119171" width="100%" height="262px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005925" width="100%" height="181px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005935" width="100%" height="145px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005944" width="100%" height="181px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005955" width="100%" height="181px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005967" width="100%" height="187px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005980" width="100%" height="235px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005993" width="100%" height="163px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

*Next: Basic Function*