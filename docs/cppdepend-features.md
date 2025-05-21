<!--
title: CppDepend Features
description: Explore the powerful features of CppDepend for static code analysis, architecture enforcement, and safety compliance in C/C++ projects.
keywords: CppDepend, static analysis, code quality, architecture, safety, MISRA, CWE, CERT, CI integration, customization, visualization
canonical: https://www.cppdepend.com/features/
-->

# ✨ CppDepend Features Overview

CppDepend helps teams develop high-quality, maintainable, and secure C/C++ software. Here’s an overview of the key capabilities that make it a comprehensive static analysis and architecture governance platform.

---

## 🧠 Code Analysis & Design Intelligence

CppDepend deeply analyzes C/C++ codebases to identify problems in design, structure, safety, and implementation.

- ✅ **Architecture validation and dependency management**
- ✅ **Custom rule engine (CQLinq)**
- ✅ **Maintainability index and technical debt tracking**
- ✅ **Code metrics, trends, and complexity analysis**
- ✅ **Advanced visualizations: graphs, matrices, treemaps**
- ✅ **Code diff between baselines**

---

## 🛡️ Safety and Standards Compliance

CppDepend supports key industry standards used in safety-critical development:

- ✔️ MISRA C++:2023
- ✔️ CERT C/C++
- ✔️ CWE Top 25
- ✔️ ISO/IEC TS 17961
- ✔️ AUTOSAR C++
- ✔️ Custom rule authoring for internal guidelines

CppDepend is widely used in automotive, aerospace, defense, medical devices, and embedded systems.

---

## 🧩 Integration and Automation

CppDepend fits seamlessly into development workflows and CI/CD pipelines.

- GitHub Actions, Azure DevOps, Jenkins, GitLab CI, and more
- CLI-based automation with HTML + JSON report outputs
- SonarQube plugin for consolidated dashboards

---

## 🕹 Visual Studio and Linux Support

CppDepend offers powerful integration on both Windows and Linux:

- Visual Studio Add-in (2017–2022)
- VisualCppDepend standalone dashboard
- Linux DevOps Edition with headless analysis and reporting

---

## 🔄 External Tools Integration

CppDepend can import and extend findings from other tools:

- Coverity
- Klocwork
- SonarQube
- Cppcheck
- Visual Studio Code Analysis
- Any XML/JSON log-based tool

Imported issues are treated as first-class citizens — visualized, queried, and tracked with native results.

---

## 📈 Visualizations & Dashboards

CppDepend helps you understand your codebase through:

- Treemaps of metric distribution
- Dependency matrices and graphs
- History and trend charts
- Customizable dashboards and technical debt indicators

---

## 🔍 Querying and Customization with CQLinq

Define your own rules, metrics, and dashboards using CQLinq:

```csharp
from m in Methods where m.CyclomaticComplexity > 20 select m
```

You can tailor the analysis to match your architecture and policies.

---

## 📊 Team Metrics and Quality Gates

- Assign ownership to projects and folders
- Monitor developer impact
- Configure quality gates
- Enforce thresholds across CI/CD

---

## 💡 Try It Yourself

- 🧪 [Download the free trial](https://www.cppdepend.com/download)
- 🎓 [CppDepend for OSS and Students](https://www.cppdepend.com/cppdepend-for-oss)
- 📘 [Explore Use Cases](https://www.cppdepend.com/use-cases)

