# More About If Statement

## If - Else Statement

If - Else statement is not an independent statement, you need to write it after an if statement.

![else_diagram](More About If Statement.assets/else_diagram.png)

![else_flowchart](More About If Statement.assets/else_flowchart.png)

When the parameter in the if statement is not True, python will execute the code under the else statement.

This is an example from *Control Flow* handout:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005466" width="100%" height="127px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Now I want to let my program output a sentence if `a` is not greater than 5. I can do this:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559123307" width="100%" height="158px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Try changing `a = 10` to `a = 2`, see what happens.

There can be only one else statement follow one is statement.

## If - Else If Statement

Else statement is useful, but sometimes you still want to check some condition before executing your second code. Else is statement is for this.

Else if statement is not an independent statement, you need to write it after an if statement.

![elif_diagram](More About If Statement.assets/elif_diagram.png)

![elif_flowchart](More About If Statement.assets/elif_flowchart.png)

This is an example from *Control Flow* handout:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559005466" width="100%" height="127px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Now, I know if variable `a` greater than 5. But in case it's not, I want to know if it's less than 3.

I can write like this:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559121981" width="100%" height="158px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

![elif_code_diagram](More About If Statement.assets/elif_code_diagram.png)

Try to change `a = 10` to `a = 1`, what will happen?

Maybe you are wondering what's the difference between the example above this and the following example:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559122171" width="100%" height="158px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

The difference is in the else if statement, if the first if parameter is true, python will not check the second parameter and skip running the second code at all. Here's an example:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559270542" width="100%" height="168px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Try changing the `elif` to `if` or the number at the first line, see what happens.

You can use more than one else if statement under one if statement, For example:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559122608" width="100%" height="194px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## If - Else If - Else Statement

You can mix them together if you want.

![elif_else_diagram](More About If Statement.assets/elif_else_diagram.png)

![elif_else_flowchart](More About If Statement.assets/elif_else_flowchart.png)

Here's some Example:

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559271084" width="100%" height="204px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

<iframe src="https://test.pegasis.site/python/editor.html?fileName=1559271196" width="100%" height="272px" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>