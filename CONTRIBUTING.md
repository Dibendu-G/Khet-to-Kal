# Contributing to Khet to Kal

Thank you for your interest in contributing to **Khet to Kal**!  
This document outlines the contribution workflow to ensure code quality, consistency, and smooth collaboration.

---

## 🧭 Branching Strategy

We follow a simple, structured branching model:

- `main` → Production branch (auto-deploys, protected)
- `develop` → Integration and staging branch
- `feature/*` → Individual feature branches

🚫 Direct commits to `main` are **not allowed**.

---

## 🔀 Development Workflow

1. Always branch out from `develop`:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b feature/<feature-name>