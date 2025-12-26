# BrainDev AI – Generated Web Application Outputs (Gemini 2.5 Pro)

This repository contains the complete set of artifacts produced during a single **end-to-end web application generation** using **BrainDev AI** with **Gemini 2.5 Pro** as the underlying Large Language Model.

The repository is intended to support **reproducibility, transparency, and qualitative inspection** of the generation pipeline described in the associated research paper. All outputs correspond to the execution of the framework on a real-world prompt and are provided *as-is*, without manual post-editing.

---

## 1. Purpose of the Repository

The goal of this repository is to:

- Provide a **full trace of the generation process**, not only the final code.
- Expose intermediate reasoning and planning artifacts produced by the framework.
- Enable researchers to analyze how high-level natural language requirements are progressively transformed into a complete full-stack web application.
- Support qualitative and structural evaluation beyond traditional snippet-level benchmarks.

This repository does **not** aim to present a production-ready application, but rather a **faithful snapshot of an AI-driven software development pipeline**.

---

## 2. Model and Configuration

- **Large Language Model:** Gemini 2.5 Pro  
- **Generation Mode:** Deterministic pipeline-based prompt chaining  
- **Framework:** BrainDev AI  
- **Methodology:** Extended Self-Planning  
- **Human Intervention:** None (fully automated)

All outputs were generated in a single run of the framework.

---

## 3. Repository Structure

The repository contains a set of text files, each corresponding to the output of a specific module in the BrainDev AI pipeline.

Typical structure:


Each file represents the **direct output of one pipeline stage**, in the exact order executed by the framework.

---

## 4. Description of the Pipeline Outputs

### 1) Pre-processing Output
Contains the normalized and structured version of the original user prompt, including application scope and high-level intent.

### 2) Requirements Engineering
Formalizes user intent into structured requirements expressed as user stories (R1, R2, …), serving as the semantic backbone of the generation process.

### 3) Architectural Design
Describes the high-level system architecture, including application layers, technology stack, component responsibilities, and data flow.

### 4) Database Schema
Defines the relational database structure, including tables, fields, data types, constraints, indexes, and relationships.

### 5) Backend Generation
Contains backend logic, API endpoint definitions, authentication mechanisms, business rules, and error-handling strategies.

### 6) Frontend Generation
Describes the frontend structure, including pages, routes, reusable components, UI behavior, and responsiveness considerations.

### 7) Integration Summary
Explains how frontend, backend, and database layers interact, focusing on API consumption, authentication flow, and data consistency.

### 8) Final Application Description
Provides a holistic overview of the generated web application, summarizing functionality, architecture, and design decisions.

---

## 5. Evaluation Context

The artifacts in this repository are used as input for the evaluation methodology described in the associated paper (e.g., Structural and Functional Coherence Evaluation).

Evaluation focuses on:
- Requirement adherence
- Cross-layer consistency
- Architectural completeness
- Functional coverage of the intended application

No manual corrections or refinements were applied before evaluation.

---

## 6. Intended Audience

This repository is intended for:
- Researchers in AI-driven software engineering
- Reviewers assessing the associated paper
- Practitioners interested in prompt-chaining and pipeline-based generation
- Anyone studying end-to-end LLM-based application generation

---

## 7. Limitations

- Generated artifacts are model-dependent.
- Results may vary with different prompts or LLM configurations.
- This repository represents a single generation instance and is not a benchmark dataset.

---

## 8. Citation

If you use or reference this repository in academic work, please cite the associated paper:

