# What Is Assembly?

> *x86-64 Windows · NASM*

---

## Intro

Hello guys, I’m **Nova**, and today I’ll be teaching the basics of **Assembly**.
I’m also a beginner, but I don’t want people to suffer reading docs or asking AI what `lea` does, so I’m making this series.

Another reason is that I found **many Linux ASM tutorials**, but not that many for **x86-64 Windows**, so yeah — here we are.

---

## Before We Start

⚠️ **Only follow along if:**

* You have a **Windows** laptop
* You are on an **x86-64 CPU**

We’ll be using **NASM** (*Netwide Assembler*) throughout this series.

With that out of the way, let’s start 🚀

---

## What Is ASM?

Before we jump into coding, let’s answer the big question:

**What is Assembly?**

Assembly is **human-readable machine code**.
It’s the lowest-level language most programmers interact with, and it’s how we talk almost directly to the system and, eventually, the kernel.

---

## What Is a Kernel?

If you don’t know what a kernel is, no problem 👍

A **kernel** is the **middleware** sitting between:

* the **Operating System**
* and the **Hardware**

On **Windows**, many important functions live inside `kernel32.dll`, which user programs call to interact with the system.

---

## What Does *x86-64* Mean?

`x86-64` is a **CPU architecture**.

Think of it like:

* **Cars** → different models
* **CPUs** → different architectures

`x86-64` simply means your CPU follows the 64-bit x86 design.

### How Do You Check If *You* Have It?

Check the file 👉 **`arch_check.md`**

---
