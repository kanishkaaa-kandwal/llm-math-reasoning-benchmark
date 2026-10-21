# LLM Mathematical Proof Verification & Audit Benchmark

A hands-on research benchmark evaluating AI-generated solutions (LLMs) across Calculus, Linear Algebra, and Discrete Mathematics for logical accuracy, step-by-step reasoning rigor, and rubric adherence.

## 📌 Project Overview
Frontier AI models often produce mathematically plausible outputs containing subtle logical errors or boundary condition misapplications. This repository provides a structured auditing framework:
- **Proof Auditing:** Identification of step-by-step logical fallacies, invalid limit operations, and missing edge cases.
- **Computational Verification:** Automated Python verification scripts to validate symbolic outputs and numerical bounds.
- **Data Structuring:** SQL schemas designed to categorize, tag, and query AI failure types by mathematical domain.

## 🛠️ Repository Contents
1. `LLM_MATH_AUDIT.pdf` - Publication-grade LaTeX audit document annotating AI proof errors and providing corrected derivations.
2. `untitled1.py` - Python script utilizing SymPy to computationally verify integration and calculus outputs.
3. `SCHEMA.SSSQL.txt` - Relational SQL schema tracking AI evaluation logs, error categories, and verification status.

## ⚙️ Tech Stack
- **Mathematics:** Calculus, Linear Algebra, Proof Verification
- **Tools & Languages:** Python (SymPy, NumPy), SQL, LaTeX, Markdown
