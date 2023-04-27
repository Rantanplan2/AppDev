Markdown offers some basic formatting syntax such as **bold**, *italic*, ***bold-italic***. It is also possible to emphasize parts of a word using b**ol**d, it*alic* or bold-***ital***ic.

Markdown also allows formatting quotes. For example: 
> Everything I have ever done, thought about, touched, felt, and experienced has 
> brought me here in this moment. As I arrive with each step, walking prompts me 
> to consider what I will do with the gift that is the present moment. 
> ([Lee, 2021](https://dx.doi.org/10.14288/1.0401116))

When you write a readme file, ask a question on StackOverflow or write documentation about your product, you often need to include code snippets. Markdown makes it very easy to format such code snippets. 

```python 
FILE_PATH = r"c:\temp\story.txt" 
# open the file and get the file object 
with open(FILE_PATH, mode="r") as input_file:
    for line in input_file.readlines(): 
        print(line) 
``` 

But you also can include inline code. For example: `print("Hello, World")` prints `Hello World` to the console.


There are two kinds of lists supported by Markdown: 

- ordered lists 
- unordered lists 

Here is an ordered list: 
1. First point 
    1. First sub-point 
2. Second point 
3. Third point 
    1. First sub-point 
    2. Second sub-point 
        1. First sub-sub-point 
        2. and so on 

Here is an unordered list: 
- First point 
  - First sub-point 
- Second point
- Third point 
  - First sub-point 
  - Second sub-point 
    - First sub-sub-point 
    - and so on 
- 1989\. A great year!

# Markdown 
## Introduction 
## Basic Syntax 
### Emphasizing 
### Links

![Vancouver](images/markdown/vancouver-map-geomo.jpg)

![Vancouver](images/markdown/vancouver-map-geomo.jpg "A map of Vancouver")

<img src="images/markdown/vancouver-map-geomo.jpg" alt="Vancouver" width="300" />


| **Logical Operator** | Description | Example (for `x = 5`) | 
| :------------------- | :----------: | ----------------------------: | 
| `&&` | and | `x < 8 && x > 4` is `True` | 
| `||` | or | `x == 4 || x == 6` is `False` | 
| `!` | not | `!False` is `True` |


| **Logical Operator** | Description | Example (for `x = 5`) | 
| :------------------- | :---------: | ----------------------------: | 
| `&&` | and | `x < 8 && x > 4` is `True` | 
| `||` | or | `x == 4 || x == 6` is `False` | 
| `!` | not | `!False` is `True` |