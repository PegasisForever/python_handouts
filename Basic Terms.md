# Basic Terms

Before continue writing more lines of code, we need to learn some basic terms. In this handout, I’m going to talk about what are them, not how to using them. We will learn to use them in detail one by one when the course goes on.

## Variable

Have you ever see something like x=10 in your math class? The “x” here represents 10.

In Python, the concept of a variable is like “x” in your math class, but have little difference.

|                            | Math                 | Python                                                       |
| -------------------------- | -------------------- | ------------------------------------------------------------ |
| Name                       | x,y or other letters | Any name you want (but needs to follow certain naming rules), for example rest, inputValue, player_head_left. |
| Value                      | numbers              | Everything. Numbers, sentences, colors, lists and a lot more. |
| Mutability (can it change) | cannot change        | variable is mutable (at least most of the time), you can change it to anything at any time you want. |

When you are giving a variable a new value, the proper way to say it is you **assigned** a variable.

### Variable Types

You cannot mention variable without mentioning variable types. Variable types describes what type of value is stored in the variable.

Here are some common types:

- Number: Don’t need to explain this much, but notice there are many kind of numbers (decimal numbers, integers, super big integers and so on). They are actually different types. But, you only need to know they are numbers.
- String: It’s definition is “a sequence of characters”, it can be only one character, a word, a sentence, or even a book. (It can be blank too)
- Boolean: True or False. If one variable’s type is Boolean, its value can only be True or False.
- Function: You will learn more about it in following section.

The type of the value you assigned to a variable don’t need to be as same as the type of the value the variable already holds.

For example, a variable “x” now holds 10 as its value. You can assign True (which is a Boolean) to “x” without any problem.

## Operator

Math class again. The concept of operators are like plus sign, minus sign in math.

Some operators in Math are very similar to math (for example +, -): they all result as a number.

Other operators in Python are not doing math, they are checking is True or False. For example they can check if the value of one variable equals another variable’s value.

## Function

You may heard about function in math class. (Hahaha math class yet again) Let’s do a comparison.

|                       | Math                   | Python                                                       |
| --------------------- | ---------------------- | ------------------------------------------------------------ |
| input (parameters)    | only numbers           | anything, same as what you can put in a variable             |
| output (return value) | one number             | anything, a function can don’t return anything, return one value or return multiple value at once. |
| what does function do | mathematic calculation | anything, maybe add two number, maybe draw an image on the screen, maybe take a picture of you. |

As you can see, functions in Python can do much more than it in math.

Functions is a type of value too. In other words, a function is stored in a variable and can be assigned to other variables like other types of the value.

## Control Flow

Finally, we got something that is not exists in your math class.

What control flow does is it controls how your code flows. (Okay I know it sounds obvious) You can use Control flow to let a certain part of your code only execute if the condition you gave it is satisfied. Or you can use control flow to run a part of your code multiple times.

## Comment

Reading “languages of computers” is sometimes boring and hard to understand. You can write some comments in your code to help yourself and others to understand your code better. When your program is executed, your comment will ignored by computer.