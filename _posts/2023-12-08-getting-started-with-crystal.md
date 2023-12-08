---
layout: post
title: Getting Started with Crystal
date: 2023-12-08 13:53
summary: Welcome to the Crystal adventure! In this kickoff post, we learned how to install Crystal on ArchLinux, making the process a breeze. After a smooth installation, we dived into coding with a classic "Hello, World!" program. Crystal's simplicity and elegance shone through as we effortlessly made our computer greet the world. The stage is set for more Crystal magic – stay tuned for the next chat where we explore the nuances of Crystal's syntax. Happy coding on your Crystal journey! ✨
---

# Getting Started with Crystal: Installation and Your First Hello World!

Hey there, fellow developers! Today, we're kicking off our journey into the wonderful world of Crystal. We'll start by installing Crystal on your ArchLinux system and writing the timeless "Hello, World!" program.

## Installing Crystal on ArchLinux

Let's get the Crystal magic flowing on ArchLinux:

1. **Open Your Terminal:**
   Fire up your terminal – it's where the adventure begins!

2. **Run the Install Command:**
   Install Crystal with this simple command:

   ```bash
   sudo pacman -S crystal
   ```

3. **Wait for the Magic:**
   Let your system do its thing. When it's done, you'll have Crystal ready to roll.

4. **Verify the Install:**
   Double-check by typing:

   ```bash
   crystal --version
   ```

   If it shows the Crystal version, you're set!

Now, let's dive into some code.

## Your First Crystal Program: Hello, World!

Let's make your computer say hi to the world! Follow these steps:

1. **Open Your Text Editor:**
   Use your favorite text editor – whatever floats your coding boat!

   ```bash
   nano hello.cr
   ```

2. **Type in the Magic Spell:**
   In your editor, add this simple Crystal spell:
    {%- highlight crystal -%}
        # hello.cr
        puts "Hello, World!"
    {%- endhighlight -%}

3. **Save and Exit:**
   Save the file, and exit your text editor.

4. **Run Your Spell:**
   Back in the terminal, navigate to your file's directory:

   ```bash
   crystal run hello.cr
   ```

   Boom! Your computer just greeted the world.

Fantastic work! You've officially started your Crystal journey by setting up Crystal and writing your first program. But wait, there's more! Stay tuned for our next chat, where we'll dive into the nitty-gritty of Crystal's syntax.

Happy coding, and welcome to the Crystal adventure!
