# Ideas on Writing Documentation

## Steo 1  - Using Codeblock.

Codeblocks in markdown makes it **easier** for *folks* to view/edit documentation.

- In order to create codeblocks in markdown, you need to use three backticks ( ``` )
- Not to be confused with quotations (') 

E.G. - With Backticks
```python
def divide_numbers(a, b):
    result = a / b
    return result

numerator = 10
denominator = 0 # Deliberate error: division by zero

result = divide_numbers(numerator, denominator)
print("Result:", result)
```

With quotations 

''' python
def divide_numbers(a, b):
    result = a / b
    return result

numerator = 10
denominator = 0 # Deliberate error: division by zero

result = divide_numbers(numerator, denominator)
print("Result:", result)

Here is where the backtick is on mac ( macbook air 2018 ) .. highlighted and surrounded by pretty yellow dots!
![backticks_mac](https://github.com/hsmithuk/github-markup-drafts/assets/86269731/be027c14-2512-49c0-9c09-99f46c85ab9c)

## Step 2 - Tables

| Title1| Title2 |
| --- | --- |
| bar | --- |
| bar | baz |

Good cloud engineers use codeblocks for both code and errors, that appear in the console.

## Step 3 - Use Markdown Task Lists
Lists which allow you to check off items.
- [x] Step 1 completed
- [ ] Step 2 completed
- [ ] Step 3 completed
- [ ] Step 4 completed

## References 
- https://twitter.com/home <sup>[1]</sup>
- https://en.wikipedia.org/wiki/ITV_Yorkshire<sup>[2]</sup>
