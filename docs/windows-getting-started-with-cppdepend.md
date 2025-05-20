<!--
title: Getting Started with CppDepend on Windows
description: Unlock the power of CppDepend to enhance your C and C++ code quality and maintainability. Learn how to get started with installation, setup, and best practices.
keywords: CppDepend, C++, Static Analysis, Windows, Setup Guide, Visual Studio Integration, Maintainability
canonical: https://www.cppdepend.com/documentation/getting-started-with-cppdepend
-->

# 🚀 Getting Started with CppDepend on Windows

CppDepend is a powerful tool to analyze, improve, and maintain your C and C++ codebases. This guide walks you through setting it up on **Windows**, including Visual Studio integration, your first analysis, and understanding the results.

---

## 📥 Download and Install CppDepend

1. Download: [CppDepend Download](https://www.cppdepend.com/download)  
2. Unzip it in a folder **outside of Program Files** (e.g., `C:\CppDepend`)  
3. Launch `VisualCppDepend.exe`  

> ⚠️ Avoid installing in `Program Files` due to Windows permission issues.

---

## 🎞️ 3-Minute Getting Started Video

📺 [Watch the video on YouTube](https://www.youtube.com/watch?v=Mo1amujyVZU)

---

## 🔍 Analyze Your C/C++ Code

### Step 1 — Launch and Create a Project

Launch `VisualCppDepend.exe` and create a new project:

<div align="center">
  <img src="https://www.cppdepend.com/img/newproject.webp" alt="New CppDepend Project" width="500"/>
</div>

---

### Step 2 — Choose Codebase View Structure

You can structure your view by:

- **Logical structure** (by namespaces):  
  <div align="center">
    <img src="https://www.cppdepend.com/img/LogicalStructure.webp" alt="Logical Structure" width="500"/>
  </div>

- **Physical structure** (by folders/files):  
  <div align="center">
    <img src="https://www.cppdepend.com/img/PhysicalStructure.webp" alt="Physical Structure" width="500"/>
  </div>

---

### Step 3 — Add Your Projects

CppDepend supports:

- `.sln`, `.vcxproj` (Visual Studio)
- QtCreator projects
- `compile_commands.json` (CMake/Ninja)
- Custom builds via [BuildMonitor](build-monitor)
- Manual setup via [ProjectMaker](project-maker)

<div align="center">
  <img src="https://www.cppdepend.com/img/addprojects.webp" alt="Add Projects" width="500"/>
</div>

---

### Step 4 — Run the Analysis

Press **F5** to start the analysis.

You’ll get an interactive dashboard with detailed metrics, graphs, and navigation tools.

<div align="center">
  <img src="https://www.cppdepend.com/img/newproject3.webp" alt="Analysis Dashboard" width="500"/>
</div>

---

## 🔌 Install the Visual Studio Add-in

Run the following installer:

```bash
CppDepend.VisualStudioExtension.Installer.exe
```

Or use the in-app installer via `VisualCppDepend.exe`.

Then:

- Open Visual Studio  
- Attach the CppDepend project to your `.sln`  
- Launch analysis and view results inside Visual Studio  

---

## 🧾 What You Learn from the Report

CppDepend provides insights such as:

- 🔢 Code and project-level metrics  
- 🧠 Interactive dependency and architecture graphs  
- 🔄 Build order and cycle detection  
- 📉 Abstractness vs. Instability visualization  
- ❌ Rule violations (CQLinq)  
- 📈 Maintainability trends and quality evolution  

---

## ⚙️ Go Further with Full Control

- Customize rules using [CQLinq](https://www.cppdepend.com/documentation/cqlinq-syntax)  
- Configure quality gates  
- Filter metrics and tailor dashboards  
- Understand how metrics relate to maintainability  

---

## 📚 Additional Resources

- 📄 [Use Cases](https://www.cppdepend.com/use-cases)  
- 📊 [Metrics Explained](https://www.cppdepend.com/documentation/code-metrics)  
- 📧 [Contact Support](mailto:support@cppdepend.com)  

---

## 🎯 Start Now

- 🧪 [Download Free Trial](https://www.cppdepend.com/download)  
- 🎓 [Free for OSS and Students](https://www.cppdepend.com/cppdepend-for-oss)
