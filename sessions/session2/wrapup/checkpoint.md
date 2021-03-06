
# Checkpoint

### Question 1

True or False: Code is hard to write so it should be hard to read?

<details>
<summary>
<b>A. </b>
True
</summary>

&emsp; :x: **INCORRECT**

> Unfortunately, some people think this is true.
</details>
<details>
<summary>
<b>B. </b>
False
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> 
</details>

### Question 2


In the Python code below, what do we call the text that starts with a `#`?

```python
# Display a greeting to the user
print("Hello, user!")
```

<details>
<summary>
<b>A. </b>
text
</summary>

&emsp; :x: **INCORRECT**

> Because it's code it's all text, but we're looking for something more specific.
</details>
<details>
<summary>
<b>B. </b>
comment
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Comments can document code or be used to temporarily prevent some code from running.
</details>
<details>
<summary>
<b>C. </b>
hashcode
</summary>

&emsp; :x: **INCORRECT**

> This is a fancy word that you'll learn about _after_ this Jumpstart course.
</details>
<details>
<summary>
<b>D. </b>
message
</summary>

&emsp; :x: **INCORRECT**

> In a way it's a message to the person reading the code, but that's not what we call it.
</details>

### Question 3

What construct do we use to conditionally execute code?

<details>
<summary>
<b>A. </b>
<code>if</code> statement
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Remember we used `if` statements to "ask questions" in code.
</details>
<details>
<summary>
<b>B. </b>
<code>choice</code>
</summary>

&emsp; :x: **INCORRECT**

> 
</details>
<details>
<summary>
<b>C. </b>
<code>condition</code>
</summary>

&emsp; :x: **INCORRECT**

> We use the term "condition" a lot when talking about code, but it's not a keyword in Python.
</details>
<details>
<summary>
<b>D. </b>
Code cannot be conditionally executed
</summary>

&emsp; :x: **INCORRECT**

> Your programs wouldn't be able to do a lot if this were true.
</details>

#### The next few questions refer to the code below:

```python
name = "Kim"
age = 20

# Part 1
if name == "Kim":
    print("Hello, Kim!")
else:
    print("Who are you?")

# Part 2
if age >= 16:
    print("You can drive")
else:
    print("Walking is good for you")

# Part 3
if age >= 21:
    print("You can drink")

# Part 4
if age < 10:
    print("You're a kid")
elif age < 20:
    print("So much teenage angst")
elif age < 30:
    print("You're still young")
elif age < 40:
    print("How did this happen?")
else:
    print("It's fine. It's all fine.")
```
### Question 4

What does the code labeled "Part 1" display?

<details>
<summary>
<b>A. </b>
<code>Hello, Kim!</code>
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Because the _value_ of the `name` variable is `"Kim"`, the `if` condition is `True`, therefore the code immediately below the `if` runs and the `else` code does not run.
</details>
<details>
<summary>
<b>B. </b>
<code>How are you?</code>
</summary>

&emsp; :x: **INCORRECT**

> Because the _value_ of the `name` variable is `"Kim"`, the `if` condition is `True`, therefore the code immediately below the `if` runs and the `else` code does not run.
</details>
<details>
<summary>
<b>C. </b>
It doesn't display anything
</summary>

&emsp; :x: **INCORRECT**

> It would be impossible for the code not to display anything. When you have an `if/else` block of code, one or the other **MUST** run, and in this case, both `print()` something.
</details>

### Question 5

What does the code labeled "Part 2" display?

<details>
<summary>
<b>A. </b>
<code>You can drive</code>
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Because the value of the `age` variable is `20` and `20` is greater than or equal to `16`, the `if` condition is `True`, therefore the code immediately below the `if` runs and the `else` code does not run.
</details>
<details>
<summary>
<b>B. </b>
<code>Walking is good for you</code>
</summary>

&emsp; :x: **INCORRECT**

> Because the value of the `age` variable is `20` and `20` is greater than or equal to `16`, the `if` condition is `True`, therefore the code immediately below the `if` runs and the `else` code does not run.
</details>
<details>
<summary>
<b>C. </b>
It doesn't display anything
</summary>

&emsp; :x: **INCORRECT**

> It would be impossible for the code not to display anything. When you have an `if/else` block of code, one or the other **MUST** run, and in this case, both `print()` something.
</details>

### Question 6

What does the code labeled "Part 3" display?

<details>
<summary>
<b>A. </b>
<code>You can drink</code>
</summary>

&emsp; :x: **INCORRECT**

> Because the value of the `age` variable is `20` and `20` is **NOT** greater than or equal to `16`, the `if` condition is `False`, therefore the code immediately below the `if` **WILL NOT RUN**, and since there is no `else`, this code will do nothing at all.
</details>
<details>
<summary>
<b>B. </b>
<code>You cannot drink</code>
</summary>

&emsp; :x: **INCORRECT**

> This string is not in the Python code, so it would be impossible for it to be printed.
</details>
<details>
<summary>
<b>C. </b>
It doesn't display anything
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Because the value of the `age` variable is `20` and `20` is **NOT** greater than or equal to `16`, the `if` condition is `False`, therefore the code immediately below the `if` **WILL NOT RUN**, and since there is no `else`, this code will do nothing at all.
</details>

### Question 7

What does the code labeled "Part 4" display?

<details>
<summary>
<b>A. </b>
<code>You're a kid</code>
</summary>

&emsp; :x: **INCORRECT**

> Because the value of the `age` variable is `20` and `20` is not less than `10`, this message will not be displayed.
</details>
<details>
<summary>
<b>B. </b>
<code>So much teenage angst</code>
</summary>

&emsp; :x: **INCORRECT**

> Because the above `if` condition was `False` and the value of the `age` variable is `20`, and `20` is not less than `20` (`20` is equal to `20`), this message will not be displayed.
</details>
<details>
<summary>
<b>C. </b>
<code>You're still young</code>
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Because the above `if` conditions were `False` and the value of the `age` variable is `20`, and `20` **is** less than `30`, this message will be displayed.
</details>
<details>
<summary>
<b>D. </b>
<code>How did this happen?</code>
</summary>

&emsp; :x: **INCORRECT**

> Because one of the previous `if/elif` conditions was `True`, the condition `age < 40` will not run, so this message will not be displayed.
</details>
<details>
<summary>
<b>E. </b>
<code>It's fine. It's all fine.</code>
</summary>

&emsp; :x: **INCORRECT**

> Because one of the previous `if/elif` conditions was `True`, the `else` code will not run, so this message will not be displayed.
</details>
<details>
<summary>
<b>F. </b>
It doesn't display anything
</summary>

&emsp; :x: **INCORRECT**

> It would be impossible for the code not to display anything. Because there is an `else` block, something will be guaranteed to run.
</details>

#### The next few questions refer to the code below:

```python
name = "SuperDog"
first_power = "covering everything with hair"
second_power = "misunderstanding object permanence"

# Part 1
bark_count = 0
while bark_count < 4:
    print("Woof!")
    bark_count = bark_count + 1

# Part 2
if name == "SuperDog" and second_power == "advanced calculus":
    print(name + " is a smart dog")
else:
    print(name + " is a dog of regular intelligence")
```
### Question 8

In "Part 1" How many `Woof!`s are printed?

<details>
<summary>
<b>A. </b>
0
</summary>

&emsp; :x: **INCORRECT**

> 
</details>
<details>
<summary>
<b>B. </b>
1
</summary>

&emsp; :x: **INCORRECT**

> 
</details>
<details>
<summary>
<b>C. </b>
2
</summary>

&emsp; :x: **INCORRECT**

> 
</details>
<details>
<summary>
<b>D. </b>
3
</summary>

&emsp; :x: **INCORRECT**

> 
</details>
<details>
<summary>
<b>E. </b>
4
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> `bark_count` is initially given the value of `0`, then each time through the `while` loop it is incremented by `1`. The loop's condition `bark_count < 4` says as long as `bark_count` is less than `4` the loop will continue to run. This means that the values of `bark_count` will be `0`, `1`, `2`, `3`, `4`. When the value becomes `4`, the `while` loop will stop and the `bark_count` will no longer be incremented.
</details>
<details>
<summary>
<b>F. </b>
5
</summary>

&emsp; :x: **INCORRECT**

> 
</details>

### Question 9

What does the code labeled "Part 2" display?

<details>
<summary>
<b>A. </b>
<code>SuperDog is a smart dog</code>
</summary>

&emsp; :x: **INCORRECT**

> Although the `name` variable has the value of `"SuperDog"`, the `second_power` variable is **NOT** equal to `"advanced calculus"`, so the `if` condition is `False` and the code immediately below the `if` does not run.
</details>
<details>
<summary>
<b>B. </b>
<code>SuperDog is a dog of regular intelligence</code>
</summary>

&emsp; :heavy_check_mark: **CORRECT**

> Although the `name` variable has the value of `"SuperDog"`, the `second_power` variable is **NOT** equal to `"advanced calculus"`, so the `if` condition is `False` and the code immediately below the `if` does not run. Instead the code immediately below the `else` runs.
</details>
<details>
<summary>
<b>C. </b>
It doesn't display anything
</summary>

&emsp; :x: **INCORRECT**

> It would be impossible for the code not to display anything. When you have an `if/else` block of code, one or the other **MUST** run, and in this case, both `print()` something.
</details>
