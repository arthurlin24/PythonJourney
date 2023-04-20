## Learning Plan for today

Day 1: 

- Install Python and VS Code (a free, popular editor)
- Learn about strings (syntax, methods) and basic operators (`+, *, %`)
- Practice with f-strings and string methods in VS Code; print some strings!



## Todo List

- [x] Install Python and VS Code

- [x] Learn about strings (syntax, methods) and basic operators (`+, *, %`)

- [x] Practice with f-strings and string methods in VS Code; print some strings!



## Summary

### Install Python and VS Code

**Computer OS: Windows 11(64-bit)**

Step 1: Get Python from [official website](https://www.python.org/downloads/) and install it.

Step 2: Download [Visual Studio Code](https://code.visualstudio.com/) and install.

Step 3: Verify if Python and VS Code are correctly installed.

### Learn about strings (syntax, methods) and basic operators (`+, *, %`)

**Python strings**
String is a collection of alphabets, words or other characters. It is one of the primitive data structures and are the building blocks for data manipulation.

**Python syntax***

The syntax of the Python programming language is the set of rules that defines how a Python program will be written and interpreted (by both the runtime system and by human readers).

Strings:
- Defined using either single quotes ('') or double quotes (" ")
- Can contain letters, numbers, symbols, spaces, etc.
- Used to represent text in Python
- Are immutable (cannot be changed)

**Python methods**

A method is a function that “belongs to” an object.


**Python operators**

Operators are used to perform operations on variables and values.

Python divides the operators in the following groups:

- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Identity operators
- Membership operators
- Bitwise operators


### Practice with f-strings and string methods in VS Code

**f-strings**
f-Strings, also called formatted string literals, strings in Python are usually enclosed within double quotes ("" ) or single quotes (''). 

To create f-strings, you only need to add an f  or an F before the opening quotes of your string.

Example:

``language = "Python"``

``school = "freeCodeCamp"``

``print(f"I'm learning {language} from {school}.")``

**String Methods:**
- Methods are called using .dot notation on a string
- Help manipulate strings without changing the original
- Some common ones:

.upper() - Converts to uppercase 

.lower() - Converts to lowercase 

.title() - Converts to title case

.strip() - Removes whitespace left and right 

.find() - Searches for a substring 

.replace() - Replaces occurrences of a substring

.split() - Splits string into list of substrings


**The Feynman-technique of learning:**

1. Pick a topic you wanna understand and start studying it

2. Pretend to teach the topic to a classroom

3. Go back to the books when you get stuck

4. Simplify and use analogies!

• If you wanna master something, teach it. 🧠

## 总结
学习 Python 语言的第一天，主要涉及到的内容就是从官网上下载适合电脑操作系统的 Python 版本，然后进行安装。正确完成安装之后，可以打开`命令提示符`输入`python`然后按回车键，这时系统将返回 Python 的版本信息。

VS Code 则是微软推出的一款功能强大的编辑器，通常将其称为 IDE（Integrated Development Environment，集成开发环境）。在目前的学习阶段，VS Code 应该可以满足全部的需求（我猜的）。

设置完开发环境之后，我们就可以正式进入学习这门语言的阶段了。编程界里有一个不成文的规定，那就是你的第一行代码是让计算机输出“你好，世界！”这句话。首先，我们要明白，这是 Python 语言当中的一个数据类型（data types），即字符串（string）。字符串是是 Python 中最常用的数据类型。

那么，如何创建一个字符串呢？用英文单引号和双引号标注即可，`print("Hello World!")`和`print('Hello World!')`是一样的，并且需要记住的是，单引号内的双引号不算结束符，双引号内的单引号不算结束符。

如果你想在字符串中同时表示单引号和双引号，那么这时候可以使用三单引号，而且三引号字符串的换行会自动转换为换行符`\n`。

**Python 运算符**

运算符（operators）用于对变量（variables）和值（values）执行操作。Python 将运算符分为以下几类:

- 算数运算符
- 赋值运算符
- 比较运算符
- 逻辑运算符
- 身份运算符
- 成员运算符
- 位运算符

**f-strings 的概念**

f-strings 也叫作格式化字符串常量（formatted string literals），可以让用户在处理字符串时更加地灵活和方便。


**字符串方法（String Methods）**

在 Python 中，方法是包含在类或对象中的函数。你可以把方法想象成对象可以做的事情。比如，如果有一个表示人的对象，它可能有吃饭、睡觉、跑步等方法（我让 Claude 以初学者的角度向我解释方法的定义，这是它的回答）。

字符串方法指的是可以在不改变原有字符串的前提下，针对该字符串执行的各种操作。举一个例子，`"hello"`是一个字符串，针对这个字符串，我们可以使其中的字母都转换为大写，输入`"hello".upper()`执行，可以得到`HELLO`。

Python有许多内置的字符串方法,允许我们对字符串执行各种操作。例如:

- s.upper()  将字符串转换为大写,如 "hello".upper() -> "HELLO"
- s.lower()  将字符串转换为小写,如 "HELLO".lower() -> "hello"
- s.title()  将字符串的每个单词的首字母都转换为大写,如 "hello world".title() -> "Hello World"
- s.startswith()  检查字符串是否以指定子字符串开头,如 "hello".startswith("he") -> True
- s.endswith()  检查字符串是否以指定子字符串结尾,如 "hello".endswith("lo") -> True
- s.split()  分割字符串,如 "hello world".split() -> ["hello", "world"]
- s.find()  在字符串中查找子字符串,如 "hello".find("l") -> 2
- s.replace()  替换字符串中的子字符串,如 "hello".replace("l","x") -> "hexlo"
- s.isalnum()  如果字符串至少有一个字符并且所有字符都是字母或数字则返回 True,如 "hello".isalnum() -> True  "hello123".isalnum() -> True
- s.isalpha()  如果字符串至少有一个字符并且所有字符都是字母则返回 True,如 "hello".isalpha() -> True  "hello123".isalpha() -> False

等等......