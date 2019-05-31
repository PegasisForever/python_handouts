# Control Flow

## Basic Structure

![basic_structure_diagram](Control Flow.assets/basic_structure_diagram.png)

### Type of the Control Statement

Some common types of control statement are if statement, while statement and for statement. We will learn how to use them in the following part of the handout.

### Parameter

Parameter tells control statement what to do. For an if statement, it's parameter tells it whether or not execute the code controlled by it.

### Indentation

Indentation is usually four spaces, it's used to tell control statement what line of code it should control. In the diagram, two indented code is controlled by the control statement, but the last line of code is not.

## If Statement

If statement needs a parameter that is Boolean type, if the parameter is true, it will perform the code in it (controlled by it).

![if_flow_chart_diagram](Control Flow.assets/if_flow_chart_diagram.png)

Here is an example:

This program check if variable `a` is greater than 5. If yes, show `Variable a is greater than 5!` in the shell, if not, do nothing.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005466" width="100%" height="127px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

![if_structure_diagram](Control Flow.assets/if_structure_diagram.png)

In this case, parameter `a > 5` is true so the code in the if statement is performed. Try change the first line `a = 10` to `a = 3`, what will happen?

## While Statement

While statement needs a parameter that is Boolean type, it performs code in it again and again until the parameter is false.

![while_flow_chart_diagram](Control Flow.assets/while_flow_chart_diagram.png)

Here's an example:

This program prints all the integers from 0 to 10.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005522" width="100%" height="145px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

![while_structure_diagram](Control Flow.assets/while_structure_diagram.png)

In this case, `number <= 10` is the parameter. When the first time while statement check the parameter, the result was true (because `number` was 0 when the program starts, and 0 is less than 10), so while statement performs the two lines of code in it. The first line of code `print (number)` outputs the value of the number, the second line of code `number = number + 1` increases `number` by 1.

After while statement performs the code in it, it checks the parameter again. Now `number` is 1, but still less than 10. So while statement performs code in it again.

After several rounds, the value of `number` reaches 11. At this time, the parameter of while statement is false. So it stop performing the code in it and program ends.

## For Statement

For statement follows a slightly different structure:

![for_structure_diagram](Control Flow.assets/for_structure_diagram.png)

For statement is used for iterating over a sequence, so its parameter needs to be a sequence. An example of sequence is String, it's “a sequence of characters”.

![for_flow_chart_diagram](Control Flow.assets/for_flow_chart_diagram.png)

Before we start our example, we need to know `range` function:

- Usage: get a sequence of integer

- Signature: `range (start, end)`

- Parameters:

  | Name  | Meaning                                             |
  | ----- | --------------------------------------------------- |
  | start | start number of the sequence                        |
  | end   | end number of the sequence (doesn't include itself) |

- Return value: `range` type, a sequence of integer from `start` to `end - 1`

Here's the example:

This program prints all the integers from 0 to 10.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005652" width="100%" height="109px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

![for_code_structure_diagram](Control Flow.assets/for_code_structure_diagram.png)

In this case, `range` function gives for statement a sequence of integers (from 0 to 10), for statement assign one of them one time to `number`, then performs the code in it: print the number.

---

Another example:

This program prints all the characters in the word "hello" one by one.

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005663" width="100%" height="109px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

`"hello"` is a value, it's type is String. String is a sequence of characters so it can be used in for statement.

## Example Code

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005672" width="100%" height="109px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005685" width="100%" height="271px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005695" width="100%" height="217px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005712" width="100%" height="145px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

(Like I said in *Operators* handout, the result of the math operation with decimal number is not always 100% accurate, but it's close enough.)

---

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005725" width="100%" height="163px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005734" width="100%" height="109px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005743" width="100%" height="253px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005752" width="100%" height="253px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005761" width="100%" height="217px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

*Next: More About If Statement*