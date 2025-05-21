<!--
title: CQLinq in CppDepend – Use Cases and Best Practices
description: Learn how to use CQLinq in CppDepend to write custom static analysis rules and enforce architecture, quality, and safety standards in C++.
keywords: CQLinq, CppDepend rules, static analysis, architecture enforcement, C++ code quality, MISRA CERT CWE
canonical: https://www.cppdepend.com/documentation/cqlinq-use-cases
-->

# 🧠 CQLinq in CppDepend – Use Cases and Best Practices

**CQLinq** (Code Query LINQ) is a powerful domain-specific query language built into CppDepend. It allows teams to inspect, enforce, and continuously monitor architectural rules, maintainability metrics, and coding standards across C/C++ codebases.

---

## 🎯 What Can You Do with CQLinq?

- ✅ Create and enforce custom architectural constraints
- ✅ Detect risky, complex, or unmaintainable code
- ✅ Track technical debt over time
- ✅ Monitor rule violations (MISRA, CERT, CWE)
- ✅ Customize dashboards and reports with your own logic

---

## 💡 Example Use Cases

### 1. Find Methods with High Cyclomatic Complexity

```csharp
from m in Methods where m.CyclomaticComplexity > 20 select m
```

Identify methods that may need refactoring for clarity and testability.

---

### 2. Prevent Layering Violations

```csharp
warnif count > 0
from t in Types 
where t.IsUsing("UI") && t.IsDeclaredIn("Core")
select t
```

Ensure code layering is respected—e.g., Core should not depend on UI.

---

### 3. Track Newly Introduced Technical Debt

```csharp
from i in Issues
where i.Severity == Severity.High && i.OccurredInThisVersion
select i
```

Catch critical issues introduced since the last version.

---

### 4. Audit MISRA Violations

```csharp
from r in Rules
where r.Name.Contains("MISRA") && r.HasBeenViolated
select r
```

Useful for certification reports and compliance preparation.

---

## 🧰 How to Use CQLinq

1. Open the VisualCppDepend dashboard
2. Navigate to **Queries and Rules**
3. Create or edit a CQLinq query
4. Run the query and inspect results
5. Optionally enforce via quality gates or CI

---

## 📊 Dashboard & Report Integration

- Add queries to dashboards and reports
- Visualize rule violations in treemaps or charts
- Export results in HTML or JSON format
- Filter by module, layer, scope, or severity

---

## 🚀 Start Writing Custom Rules

CppDepend ships with 200+ default queries covering metrics, maintainability, standards, and design. You can edit these or create new ones.

---

## 🧪 Try CQLinq in CppDepend

- 🧪 [Download Free Trial](https://www.cppdepend.com/download)
- 🎓 [CppDepend for OSS & Students](https://www.cppdepend.com/cppdepend-for-oss)
- 📘 [Official Documentation](https://www.cppdepend.com/documentation)


