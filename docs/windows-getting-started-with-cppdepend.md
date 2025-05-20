<!--
title: Getting Started with CppDepend on Windows
description: Unlock the power of CppDepend to enhance your C and C++ code quality and maintainability. Learn how to get started with installation, setup, and best practices.
keywords: CppDepend, C++, Static Analysis, Windows, Setup Guide, Visual Studio Integration, Maintainability
canonical: https://www.cppdepend.com/documentation/getting-started-with-cppdepend
-->

# 🚀 Getting Started with CppDepend on Windows

CppDepend is a powerful tool to analyze, improve, and maintain your C and C++ codebases. This guide walks you through how to set it up on **Windows**, including Visual Studio integration, first analysis steps, and interpreting the results.

---

## 📥 Download and Install CppDepend

1. Download the installer: [CppDepend Download](https://www.cppdepend.com/download)
2. Unzip it in a folder **outside of Program Files** (e.g., `C:\CppDepend`)
3. Run `VisualCppDepend.exe`

> ⚠️ Do not install in `Program Files` due to Windows permissions

---

## 🎞️ 3-Minute Getting Started Video

📺 [Watch the video on YouTube](https://www.youtube.com/watch?v=Mo1amujyVZU)

---

## 🔍 Analyze Your C/C++ Code

Steps:

- Launch `VisualCppDepend.exe`
- Create a new project
  <div align="left">
  <img src="https://www.cppdepend.com/img/newproject.webp" alt="New CppDepend Project" width="400"/>
</div>
- Choose how to structure your codebase view:
  - Logical structure (by namespaces)
  - Physical structure (by folders/files)
- Add your projects:
  - `.sln`, `.vcxproj` (Visual Studio)
  - QtCreator projects
  - `compile_commands.json` (from CMake/Ninja)
  - Custom build via [BuildMonitor](build-monitor)
  - Manual setup via [ProjectMaker](project-maker)
- Press **F5** to run analysis

📸 Output: Interactive dashboard with metrics, graphs, and more

---

## 🔌 Install Visual Studio Add-in

Run:

```bash
CppDepend.VisualStudioExtension.Installer.exe
```

Or use the in-app installer in VisualCppDepend.

Then:

- Open Visual Studio
- Attach CppDepend project to your `.sln`
- Launch analysis and view results inside Visual Studio

---

## 🧾 What You Learn from the Report

CppDepend reports give insight into:

- 🔢 Application and project-level metrics
- 🧠 Visual structural views
- 🔄 Build order and dependency cycles
- 📉 Abstractness vs. Instability chart
- ❌ Rule violations (via CQLinq queries)
- 🧮 Trends and maintainability tracking

---

## ⚙️ Go Further with Control

- Understand metrics and how they relate to maintainability
- Learn and customize [CQLinq rules](https://www.cppdepend.com/documentation/cqlinq-syntax)
- Filter and configure the dashboard views
- Tune your quality gates

---

## 📚 Additional Resources

- [Use Cases](https://www.cppdepend.com/use-cases)
- [Metrics Explained](https://www.cppdepend.com/documentation/code-metrics)
- [Support](mailto:support@cppdepend.com)

---

## 🎯 Start Now

- 🧪 [Download Free Trial](https://www.cppdepend.com/download)
- 🎓 [Free for OSS and Students](https://www.cppdepend.com/cppdepend-for-oss)

