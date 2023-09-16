+++
title = 'Printing'
date = 2023-09-14T10:34:18-06:00
draft = false
weight = 1
+++

{{% notice style="grey" title="Definitions" icon="book" %}}
{{<snippet "glossary/syntax.md">}}

{{<snippet "glossary/exceptions_errors.md">}}
{{% /notice %}}

This is a `print` statement. 
```python
print(“Hello World”)
```

Learning this first allows you to see code actually doing something.  Most code doesn’t give your feedback when it’s running unless you add code to the program to give you feedback.  Using the `print` statement is one way to accomplish this.

There are rules that you must follow in order for `print` to work, otherwise you’ll get an error. `print` is written in all lowercase. Whatever it is you are printing must always be in double quotes or single quotes, or it must be a variable.  We’ll talk about variables in the next section so we’ll just focus on quotes.

Double quotes: “
Single quotes: ‘

The Python language doesn’t care which of the two you use so long as you’re consistent. You must use the same type of quote at the beginning and the end.

```python
# properly quoted strings
print(“Hi”)
print(‘there’)

# improperly quoted strings
print(“no worky)
print(still not worky”)
print(‘nope nada”)
```

If you tried running the improperly formatted print statements you definitely received errors from Thonny.

This is due to the syntax, the way and style of coding for a particular language, not being proper.  Each language has its own syntax, however, what you will be learning are the concepts of programming.  Focusing on the concepts initially will allow you to learn new programming languages faster.

