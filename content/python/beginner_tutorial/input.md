+++
title = 'Input'
date = 2023-09-15T23:50:41-06:00
draft = true
weight = 3
+++

Most programs rely on data being provided to it; we call this input. Input can be provided by a person, also called a user, or another program. Programs are built to solve problems. In order to provide the solution to the program it was built to solve it needs to know some information about the problem. The problem we want to solve in this section is to have our program repeat the text we give it.

Run this code
```python
input()
```

Interesting, it doesn't look like anything happened. However, in the Shell pane it hasn't returned to the prompt `>>>`. Click inside the Shell and type something. Well, it allows you to type but it still hasn't returned to the prompt `>>>`. Press enter. There we go now we're returned to the prompt. It doesn't seem like any was done. Let's assign the `input()` to a variable.

{{% notice style="note" title="Note" %}}
Be sure you have the Variables pane shown. If it's not,
{{<snippet "instructions/variables_pane.md">}}.
{{% /notice %}}

```python
user_input = input()
```

