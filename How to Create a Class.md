# How to Create a Class

## Basic Structure

![class_basic_structure_diagram](../Python%20Handout/How%20to%20Create%20a%20Class.assets/class_basic_structure_diagram.png)

### Method

A method is like a normal function, except the name first parameter must be `self`. `self` is a variable that contains the instance which this method in. (for example, the value of `me` in the examples before)  You can get attributes of the instance from `self`.

Read this piece of code from the example before, the method `selfIntro` have one parameter.(but when you invoke it, you don’t need to give it any parameter because python automatically fills the first parameter with the instance you are using) In the second line, you get the name and age attributes from `self`, an instance of Person, and print them out.

In the example before, when `me.selfIntro()` runs, python use `me` as the value for parameter `self`.

```python
def selfIntro(self):
    print("I'm " + self.name + " and I'm " + str(self.age) + " years' old.")
```

### \_\_init\_\_ Method

\_\_init\_\_ Method is a special method, it invokes when you instantiate a class.

In the example before, when `me = Person("pega",16,"male")` runs, python invokes this method and give parameters `"pega",16,"male"` to it.

Because value from the parameters will disappear after this method ends, so it assign them to the attributes of the instance.(represented by `self`)

```python
def __init__(self, name, age, gender):
    self.name = name
    self.age = age
    self.gender = gender
```

Next: *Use Tkinter to Build GUI Applications*