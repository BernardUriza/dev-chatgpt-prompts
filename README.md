# 🤖 DEV AI Prompts

A tight collection of copy/paste prompts for everyday dev work. No setup, no fill-in-the-blanks — just paste and go. 🚀

## Table of Contents

- [✂️ Split into Multiple Methods](#️-split-into-multiple-methods)
- [🔍 Review & Reflect](#-review--reflect)
- [🧹 Refactor for Readability](#-refactor-for-readability)
- [🐛 Find & Fix Errors](#-find--fix-errors)
- [✅ Generate Unit Tests](#-generate-unit-tests)
- [🗺️ Plan a Feature Across Layers](#️-plan-a-feature-across-layers)
- [🔒 Privacy & Security Audit](#-privacy--security-audit)
- [🧠 Debug AI Output Quality](#-debug-ai-output-quality)
- [⚡ Optimize a Slow Operation](#-optimize-a-slow-operation)
- [🎨 UI/UX Consistency Check](#-uiux-consistency-check)

---

## ✂️ Split into Multiple Methods

> Long function doing too much? Break it down.

```
Look at the code I'm sharing. Identify all the responsibilities it handles and refactor it into smaller, focused methods — each with a single, clear purpose. Keep the original behavior intact. Show the refactored version. If neccesary, review the code and re-write it to modern programming standards and formatting.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🔍 Review & Reflect

> Get a review, then make the AI question itself.

```
Review the code I'm about to share. List any logical errors, security concerns, or bad practices you find — but don't fix anything yet. Just give me the list.
```

Then follow up with:

```
Now review your own recommendations. Were any of them wrong, redundant, or missing something important? Correct yourself before we proceed.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🧹 Refactor for Readability

> Clean it up without changing what it does.

```
Refactor the code I'm sharing to improve readability and maintainability. Apply clean code principles: meaningful names, small functions, no duplication, clear intent. Do not change the behavior — only improve the structure.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🐛 Find & Fix Errors

> Drop your broken code, get it back working.

```
I have a bug. Here's my code and the error I'm getting. Identify the root cause, explain what went wrong in plain terms, and give me the corrected version with a brief explanation of the fix.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## ✅ Generate Unit Tests

> Cover the happy path and the failure case.

```
Write unit tests for the code I'm sharing. Include at least one test for a successful scenario and one for a failure or edge case. Make the tests clear and easy to understand.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🗺️ Plan a Feature Across Layers

> For features that touch frontend, backend, and data — before writing a single line.

```
I need to implement a new feature in my application. I'll describe what it should do from the user's perspective. Your job is to break it down into layers: what changes in the UI, what the backend needs to handle, what data needs to be stored or retrieved, and what edge cases to watch out for. Give me a clear, ordered implementation plan before any code is written.

Feature: [describe it here]
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🔒 Privacy & Security Audit

> Catch data exposure issues before they reach production.

```
Review the code I'm sharing with a focus on data privacy and security. Look for: sensitive data being logged or exposed, missing authorization checks, unvalidated inputs that reach storage or external calls, and any pattern where user data could leak across boundaries. List every concern with a short explanation of the risk and the recommended fix.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🧠 Debug AI Output Quality

> When your AI integration returns wrong, hallucinated, or irrelevant responses.

```
My AI-powered feature is returning poor quality responses. I'll share the prompt or retrieval logic I'm using and some examples of bad outputs. Analyze what's likely causing the degradation — bad context, vague instructions, missing constraints, retrieval issues — and suggest concrete changes to improve output quality. Don't rewrite everything, just identify what's broken and why.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## ⚡ Optimize a Slow Operation

> When something works but takes too long.

```
The operation I'm sharing is too slow for production use. Analyze the code and identify the main performance bottlenecks. Explain why each one is slow, then propose the most impactful optimizations in order of priority. Focus on changes with real-world impact — no premature micro-optimizations.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>

---

## 🎨 UI/UX Consistency Check

> Before shipping UI changes — make sure nothing looks broken across states.

```
I'm going to describe or show you a UI component or screen. Review it for consistency issues: visual states that are missing (loading, empty, error), interactions that feel incomplete, layout that might break at different sizes, and anything that doesn't match expected user behavior. Don't suggest redesigns — just flag what's inconsistent or incomplete.
```

<sup>[⬆️ Back to top](#table-of-contents)</sup>
