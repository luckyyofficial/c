# 💻 Introduction to C Language

C is a **general-purpose, procedural programming language** developed in the early 1970s by **Dennis Ritchie** at Bell Labs. It is known for its **efficiency, speed, and low-level access to memory**, which makes it a foundational language for many modern systems.

### 🔎 Key Features:
- 🔧 **Procedural** and **structured** programming style  
- ⚙️ Low-level memory manipulation via pointers  
- 💡 Powerful and efficient for system-level programming  
- 🌐 Portable and widely supported across platforms  
- 🧱 Forms the basis for many other languages (C++, Java, etc.)

### 📘 Simple Example:
```c
#include <stdio.h>
  
int main() {
    printf("Hello, World!\n");
    return 0;
}  
# 🧱 Basic C Program Structure (For Beginners)
 
Every C program follows a standard format. If you are just getting started with C programming, understanding this basic structure is your first step.
 
---

## 📄 Standard C Program Template (Explained)

```c
#include <stdio.h> 
// This line includes the Standard Input Output library.
// It allows us to use functions like printf() to display output.

int main() 
// This is the starting point of every C program.
// The program starts running from the main() function.
{
    printf("Hello, World!\n"); 
    // This line prints the text "Hello, World!" followed by a new line.

    return 0; 
    // This ends the program and returns 0 to show it ran successfully.
}
# C Language

## Introduction

**C** is a versatile (adaptable) and powerful programming language that allows developers to create efficient and portable software. Its known for its close-to-hardware capabilities, making it suitable for systems programming and embedded systems.

C features a **procedural programming model** and is widely used in software development, including:

- Operating systems  
- Game development  
- Embedded systems  
- Firmware  
- Desktop applications  

It provides **low-level control** over computer hardware while maintaining a **simple and straightforward structure**.

---

## How to Use C Language

### 1. Write Code

Use a **text editor** (like VS Code, Sublime Text, or even Notepad) to write your C code.

A basic C program typically includes the `main()` function, which is the entry point for execution.

Example:
```c
#include <stdio.h>

int main() {
    printf("Hello, World!");
    return 0;
}
  
  
