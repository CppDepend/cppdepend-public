<!--
title: Getting Started with CppDepend on Linux
description: Step-by-step guide to install, activate, and run CppDepend on Linux. Supports Ubuntu, Debian, Fedora, and other distributions.
keywords: cppdepend linux, install cppdepend ubuntu, cppdepend fedora, static analysis c++, linux integration
canonical: https://www.cppdepend.com/documentation/getting-started-with-cppdepend-linux
-->

# 🐧 Getting Started with CppDepend on Linux

CppDepend supports Linux environments for teams who prefer building and analyzing native code on non-Windows platforms. Here's how to install and get started.

---

## 🧱 System Requirements

CppDepend on Linux requires:

- Mono >= 6.12 (Mono runtime for .NET compatibility)
- Ubuntu, Debian, Fedora, or any distro with Mono support
- Access to your source code and compilation scripts (makefiles, cmake, etc.)

---

## 📦 Step 1: Install Mono

Use the package manager for your distribution:

**Ubuntu/Debian:**

```bash
sudo apt update
sudo apt install mono-complete

