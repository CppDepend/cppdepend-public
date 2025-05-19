<!--
title: Getting Started with CppDepend on Linux
description: Follow our step-by-step guide to install and set up CppDepend on Linux. Improve C and C++ code quality and maintainability on Ubuntu and other Linux distributions.
keywords: CppDepend, Linux, C++, Static Analysis, Developer Edition, DevOps Edition, Ubuntu, Code Quality, Maintainability
canonical: https://www.cppdepend.com/documentation/getting-started-with-cppdepend-linux
-->

# 🐧 Getting Started with CppDepend on Linux

CppDepend is a powerful static analysis tool for C/C++ developers. This guide walks you through how to set up **CppDepend on Linux**, including Ubuntu and other distributions.

---

## 🧭 Choose the Right Edition

CppDepend offers two editions for Linux:

- **Developer Edition**: Available for Ubuntu 18.04 / 20.04 / 22.04  
- **DevOps Edition**: Works across all Linux distributions

📥 [Download CppDepend](https://www.cppdepend.com/download)

---

## 🧑‍💻 Developer Edition (Ubuntu 18.04 / 20.04 / 22.04)

Steps:

1. **Download** the Developer Edition from the [official download page](https://www.cppdepend.com/download).
2. Open a terminal and navigate to the installation directory.
3. Launch the visual UI:

```bash
./VisualCppDepend.sh
```

4. Create a new project and import your build data using a `compile_commands.json` file.
5. Run the analysis.
6. View your analysis results in the CppDepend Dashboard.

📸 Screenshots:  
![New Project](https://www.cppdepend.com/img/linux1.png)  
![Add Project](https://www.cppdepend.com/img/linux2.png)  
![Run Analysis](https://www.cppdepend.com/img/linux3.png)  
![Dashboard](https://www.cppdepend.com/img/linux7.png)

---

## ⚙️ DevOps Edition (All Linux Distributions)

Steps:

1. Download the DevOps Edition from the [CppDepend download page](https://www.cppdepend.com/download).
2. Open a terminal and run:

```bash
./CppDepend compilation_commands.json /OutDir /home/test/CppDependOut
```

- `compilation_commands.json`: Your compile DB file
- `/home/test/CppDependOut`: Output directory for the HTML report

📸 Example Output:  
![Report](https://www.cppdepend.com/img/V4Report.png)

---

## 🔍 Edition Comparison: Developer vs DevOps

| Feature                                       | Developer Edition | DevOps Edition |
|----------------------------------------------|-------------------|----------------|
| Visual Studio Integration (Windows only)     | ✅                | ❌             |
| Visual Dashboard (Linux Ubuntu + Windows)    | ✅                | ❌             |
| Interactive Graphs & Matrices                | ✅                | ❌             |
| Treemapping Visualization                    | ✅                | ❌             |
| CI Integration (Jenkins, TeamCity, etc.)     | ❌                | ✅             |
| HTML Report Generation via Console           | ❌                | ✅             |
| SonarQube Plugin                             | ❌                | ✅             |
| Quality Gates & Build Failure Conditions     | ❌                | ✅             |
| Rule Editing, Technical Debt, Metrics, etc.  | ✅                | ✅             |

ℹ️ The trial version includes both editions.

---

## 💬 Need Help?

If you run into issues, reach out at:  
📧 [support@cppdepend.com](mailto:support@cppdepend.com)

---

## ✅ Get Started Now

- 🔽 [Download CppDepend](https://www.cppdepend.com/download)  
- 🎓 [CppDepend for OSS and Students](https://www.cppdepend.com/cppdepend-for-oss)
