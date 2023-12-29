---
layout: post
title: Control Flow in Crystal
date: 2023-12-29 14:56
summary: Explore the pathways of control flow in Crystal! From conditional statements to loops, learn how to direct the flow of your programs with elegance and precision. Master the art of decision-making and repetition in Crystal programming. Dive into the details and enhance your coding skills.
---

# Control Flow in Crystal: Navigating the Programming Pathways

Welcome back, Crystal adventurers! In this post, we'll delve into the fascinating realm of control flow in Crystal. Control flow structures are the building blocks that enable you to direct the execution path of your programs. Whether it's making decisions with conditionals or repeating tasks with loops, mastering control flow is essential for writing dynamic and responsive code.

## Conditional Statements

Crystal provides expressive and powerful conditional statements, allowing you to make decisions based on different conditions. Let's explore the key constructs:

### `if` Statements

Use the `if` statement for straightforward conditional branching:

{%- highlight crystal -%}
age = 25

if age >= 18
  puts "You're an adult."
else
  puts "You're a minor."
end
{%- endhighlight -%}

### `case` Statements

When dealing with multiple conditions, the `case` statement provides an elegant solution:

{%- highlight crystal -%}
day = "Monday"

case day
when "Saturday", "Sunday"
  puts "It's the weekend!"
when "Monday"
  puts "Start of the workweek."
else
  puts "Midweek adventures await!"
end
{%- endhighlight -%}

## Loops

Loops allow you to repeat a block of code until a certain condition is met. Crystal offers a variety of looping structures to suit different scenarios.

### `while` Loop

The `while` loop repeats a block of code while a given condition is true:

{%- highlight crystal -%}
count = 1

while count <= 5
  puts "Iteration #{count}"
  count += 1
end
{%- endhighlight -%}

### `until` Loop

The `until` loop, on the other hand, repeats until a condition becomes true:

{%- highlight crystal -%}
number = 0

until number > 5
  puts "Current number: #{number}"
  number += 1
end
{%- endhighlight -%}

### Note: No `for` Loop in Crystal

As of now, Crystal does not have a `for` loop. We eagerly await its potential inclusion in future versions!

## Conclusion

Congratulations! You've now embarked on the journey of control flow in Crystal. Understanding conditional statements and loops equips you with the tools to make decisions and control the repetition of tasks in your programs. Stay tuned for our next exploration into functions and methods in Crystal programming.

Happy coding, and may your Crystal adventures continue to shine brightly!
