---
layout: essay
type: essay
title: "Finding Inner Peace through Code Standards"
# All dates must be YYYY-MM-DD format!
date: 2024-02-07
published: true
labels:
  - Coding Standards
  - ESLint
  - IntelliJ
---
<p align="center">
<img width="400px" class="img-fluid" src="../img/ESLINT error.png">
</p>

## Coding Standards

Coding standards are a set of guidelines that are used to create consistent, high-quality code. They help programmers develop cleaner, more readable, and efficient code. It is important to follow coding standards because it offers a uniform format that makes it easier to facilitate collaboration among developers. If everybody follows a universal coding standard, it makes it much easier for someone new to your code to understand and find your way around your code. For example, if a team collaborated on a code together and everybody had different coding standards, it would be hard to read as each person's style would be different and blatant that multiple people worked on different sections. In ideal circumstances, the source code would look like a single developer wrote it if everybody followed the same coding standard.

## Coding Standards to Follow and Practice

1) **Focus on code readability**: A good code is easily readable, which means it optimizes space and time. Some rules to follow to make your code more readable would be to avoid long lines, which helps to write the code in as few lines as possible. Segment appropriate codes into the same section using paragraphs. Avoid complex nested code, which makes it difficult to maintain, debug, and read.
   
2) **Standard headers for different modules**: The header of different modules should follow some standard format. For example, each header should contain the name, date, and author of the module. As well as modification history, a summary of what the module is about and does, different functions with their input-output parameters, and global variables accessed by the module. It makes it easier to understand and maintain code when there is a standard for headers for different modules with a singular format.
   
3) **Indentation**: Using consistent indentation improves readability. For example, using spaces after a comma between function arguments. Each nested block should be properly indented. Using indentation to make the beginning and ending of each block in the program.
   
4) **Formatting**: Be consistent in formatting throughout the program. Using an automated tool or formatter ensures consistency throughout the code.
   
5) **Naming Conventions**: Meaningful and understandable variable names help programmers understand what it is being used for. It is important to use descriptive unique names for variables, functions, and classes. A single variable should not be assigned multiple values for numerous functions. Local variables and functions should be named using camel case lettering while global variables should start with a capital letter. It is also better to avoid using numbers in variable names.
    
6) **Comments**: Writing clear concise comments for code sections help readers understand what your code is trying to do. You shouldn't assume everyone reading your code will immediately understand what it is doing without clarification. It is especially important to do so in complex sections but make sure to write enough to provide the proper context without overexplainning.

## My Experience Using ESLint with IntelliJ

From the beginning of my coding journey, we are taught the basics of coding standards, such as proper naming conventions, some indentation rules, headers, and writing comments. In the beginning, I didn't fully understand the importance of following a universal coding standard but as I started to learn more about coding, it became more apparent each time. Especially when I first started learning Java, whenever I looked at new pieces of code, I realized the comments really helped me understand what each line of function was doing. Plus the indentation helps understand what each line of code is used for and if it's part of another function. 

I am currently new to using ESLint with IntelliJ. My first impression was that I actually really liked ESLint's check function. I usually make a lot of syntax mistakes, sometimes unknowingly so with ESLint, it accurately identifies exactly what I have to fix. It helps my code appear more consistent as well as avoiding bugs before I actually run my code. However, when I had to do the practice WODs, I found myself a little stressed over getting the green checkmarks for ESLint on IntelliJ. Since WODS are of a time-crunch nature, with ESLint identifying and reporting errors or bad coding standards in my code, it significantly slowed me down, where I would have to go back and keep fixing my code. Overall, I think I appreciate ESLint's plugin on IntelliJ as it helps me identify mistakes and I'm hoping that I'll stop making small mistakes in my coding standard and errors along the way through the habitual fixes.
