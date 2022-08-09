---
title: "MD Web"
permalink: /
layout: default
---

### This is my first Markdown-based website

```py
from dataclasses import dataclass

@dataclass
class Person:
  name: str
  age: int
```

## Learn [Rust Programming Language](https://www.rust-lang.org/)
### Getting Started
Let’s start your Rust journey! There’s a lot to learn, but every journey starts somewhere. In this chapter, we’ll discuss:
- Installing Rust on Linux, macOS, and Windows
- Writing a program that prints `Hello, world!`
- Using `cargo`, Rust’s package manager and build system
### Installation
The first step is to install Rust. We’ll download Rust through `rustup`, a command line tool for managing Rust versions and associated tools. You’ll need an internet connection for the download.
> Note: If you prefer not to use `rustup` for some reason, please see the Other Rust Installation Methods page for more options.
The following steps install the latest stable version of the Rust compiler. Rust’s stability guarantees ensure that all the examples in the book that compile will continue to compile with newer Rust versions. The output might differ slightly between versions, because Rust often improves error messages and warnings. In other words, any newer, stable version of Rust you install using these steps should work as expected with the content of this book.
> ### Command Line Notation
In this chapter and throughout the book, we’ll show some commands used in the terminal. Lines that you should enter in a terminal all start with $. You don’t need to type in the $ character; it indicates the start of each command. Lines that don’t start with $ typically show the output of the previous command. Additionally, PowerShell-specific examples will use > rather than $.
