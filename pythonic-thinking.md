<!--
https://link-springer-com.ezproxy.unal.edu.co/chapter/10.1007/978-1-4842-4878-2_1
-->
# Pythonic Thinking

The thing that sets Python apart from other languages is that it is a simple language with a lot of depth. Because it’s simple, it’s much more important to write code cautiously, especially in a big project, because it’s easy for the code to become complex and bloated. Python has a philosophy called the Zen of Python, which emphasizes simplicity over complexity.1

In this chapter, you will learn about some common practices that can help you to make your Python code more readable and simpler. I will cover some well-known practices, as well as some that might not be so well-known. While writing your next project or working on your current project, make sure that you are well aware of these Python practices so you can improve your code.

## Write Pythonic Code

Python has some official documentation called PEP8 that defines best practices for writing Pythonic code. This style guide has evolved over time. You can check it out at https://www.python.org/dev/peps/pep-0008/ .

In this chapter, you will focus on some common practices defined in PEP8 and see how following those rules can benefit you as a developer.

### Naming

As a developer, I have worked with different languages such as Java, NodeJS, Perl, and Golang. All these languages have naming conventions for variables, functions, classes, and so on. Python also recommends using naming conventions. I will discuss some of the naming conventions in this section that you should follow while writing Python code.

#### Variables and Functions

You should name functions and variables in lowercase with the words separated by underscores, as this will improve readability. See Listing 1-1.

```pyton
names = "Python"                               # variable name
job_title = "Software Engineer"                # variable name with underscore
populated_countries_list = []                  # variable name with underscore
```
