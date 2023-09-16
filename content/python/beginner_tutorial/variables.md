+++
title = 'Variables'
date = 2023-09-14T10:37:19-06:00
draft = false
weight = 2
+++

Imagine a variable is like a box that can hold different things, like toys or snacks. In programming, a variable is a special kind of box that holds information like numbers or words. We give each box a name, like "score" or "name," so we can use it to remember and change information while we're writing computer programs. It's like having different boxes to store different things in a game or a story!

Storing data temporarily is often needed when writing programs. Variables allow you to reference data by the variable name rather than the actual data.  This is important since programs can take in different kinds of data which we'll use at different parts of the program.

Here is an example of how to declare a variable.
```python
greeting = "Hi"
```
You'll notice that if you run this code it seems like it doesn't do anything. However, it is in fact setting the variable `greeting` to the value `"Hi"`. In Thonny, 
{{<snippet "instructions/variables_pane.md">}}.
 This will open a new pane to the right of the main editor. Now you should see `greeting` under the Name column and `"Hi"` under the Value column.

Now before running the next example I want you think about what you expect the code to do.
```python
greeting = "Hi"
greeting = "Bye"
```
Did you get it right? If so, great job! If not, it's okay you're learning!

In order for you to understand what is going on let's use the debugging features of Thonny. There is a little bug looking icon *insert image?* at the top next to the green play button, click it. You should now see the first line highlighted in yellow. Click the yellow arrow at the top that has the arrow head going in-between the two dots, this button is labeled Step into. Click this button until you see `greeting` displayed in the Variables pane and then stop. Look at the value of `greeting`. Now click Step into until you see `greeting` change values.

{{% expand title="Output" %}}
The reason `greeting` has the value of `"Bye"` is cause it was overwritten and given a new value.
{{% /expand %}}

Naming of the variables is an important part of writing code. They should be meaningful names. This is so other people, or yourself sometime in the future, understands what the variable is used for when reading the code. There needs to be a balance of what the variable is named without making it too long.

```python
# Proper naming
greeting = "Hi"
full_name = "Santa Maria"
# Improper naming
g = "Hi"
fn = "Santa Maria"
# This is too much
first_and_last_name_of_the_person = "Billy Bob"
```
Now that you have a basic understand of variables play around in Thonny by making other variables. Then see if you can use the print function to print the variables you created.

{{% expand title="My Solution" %}}
```python
greeting = "Sup"
print(greeting)
# Bonus solution
print(greeting, "Homie")
```
{{% /expand %}}