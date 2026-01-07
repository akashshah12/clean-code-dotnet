# 🚀 Clean Code in .NET (C#)

This repository demonstrates **clean code principles in C#** using **simple, real-world examples**.  
Each concept is explained using **bad vs good implementations** to clearly show how small changes improve **readability, maintainability, and collaboration**.

This repo is intended for **developers, senior engineers, and aspiring Tech Leads** who want to write **clear and sustainable code**.

---

## 📌 Problem Statement

Many applications fail not because of complex business logic, but due to:
- Poor naming
- Long and unclear methods
- God classes
- Excessive comments instead of readable code
- Inconsistent error handling

Such issues slow down teams, increase bugs, and make onboarding difficult.

---

## 🎯 Objective

The goal of this repository is to:
- Demonstrate **clean coding practices** in .NET
- Show **how bad code can be refactored into clean code**
- Encourage **code that explains itself**
- Promote **team-friendly and maintainable design**

---

## 🧠 Key Concepts Covered

- Meaningful naming
- Small and focused methods
- Single Responsibility Principle (SRP)
- Self-documenting code
- Proper exception handling
- Refactoring techniques

---

## 🏗️ Project Structure

```text
clean-code-dotnet/
│
├── src/
│   ├── Naming/
│   │   ├── BadNamingExample.cs
│   │   └── GoodNamingExample.cs
│   │
│   ├── Methods/
│   │   ├── LongMethodBad.cs
│   │   └── SmallMethodsGood.cs
│   │
│   ├── Classes/
│   │   ├── GodClassBad.cs
│   │   └── SingleResponsibilityGood.cs
│   │
│   ├── ErrorHandling/
│   │   ├── TryCatchEverywhereBad.cs
│   │   └── ProperExceptionHandlingGood.cs
│   │
│   └── Program.cs
│
└── docs/
    └── clean-code-guidelines.md