# Contributing to No-Code Architects Toolkit

Thanks for your interest in contributing! ❤️

This project exists to help **non-technical creators build smarter systems** — so every contribution must be:

✅ Simple
✅ Useful
✅ Low-maintenance

We welcome contributors, **but we’re not here to clean up messy code, finish your half-built idea, or debug your mistakes**.

> And if you like the project but don't know how to code.
>
> You can still support us in other ways:
>
> * ⭐ Star the project
> * 📣 Share it on social media
> * 🌲 Refer it to a friend or your community
> * 💸 [Sponsor the project](#)

If you need help or have questions, check out the github [discussions](https://github.com/stephengpope/no-code-architects-toolkit/discussions) or join the [community](https://www.skool.com/no-code-architects/about?ref=2f302c52a77541efa2dd5e8b27f3f8c9).

---

## Table of Contents

* [What We Accept](#what-we-accept-)
* [What We Reject](#what-we-reject-)
* [Feature Evaluation Framework](#feature-evaluation-framework)
* [Technical Guidelines](#technical-guidelines)
* [Contribution Types](#contribution-types)
* [Final Thoughts](#final-thoughts-%EF%B8%8F)

---

## What We Accept ✅

* Solves **common no-code challenges**
* **Reduces cost** or replaces paid APIs/tools
* Requires minimal input (has defaults)
* Is understandable by **non-technical users**
* Works out-of-the-box, no setup required
* One-time integrations — **no constant maintenance needed**
* Uses **existing input/output naming conventions**
* Follows our directory and structure conventions

---

## What We Reject ❌

* Features built for one person or edge-case
* Inconsistent input/output field names
* Requires polling, retries, or callback logic
* Needs babysitting or breaks frequently
* Lacks error handling or code comments
* Includes unused code, requirements, or bloat
* Adds huge packages that inflate Docker image size
* Leaves us with more work to do

---

## Feature Evaluation Framework

| Category              | Ask This...                                    | ✅ Accept if...                                 | ❌ Reject if...                             |
| --------------------- | ---------------------------------------------- | ---------------------------------------------- | ------------------------------------------ |
| **Mission Fit**       | Does this reduce cost or unify tools?          | Replaces APIs, reduces costs or complexity     | Adds noise or solves narrow edge cases     |
| **Input Familiarity** | Are inputs familiar (`file_url`, `text`, etc)? | Uses standard names/types already in use       | Introduces new terms for same ideas        |
| **Input Clarity**     | Would a non-tech user know what to enter?      | Inputs like "Enter URL", "Choose format"       | Needs tech explanation or experimentation  |
| **Output Usefulness** | Can this plug straight into Make/Zapier?       | Returns clean files, text, URLs                | Returns raw data or deep nested structures |
| **Reliability**       | Will it just work?                             | API is stable, no retries, consistent behavior | Depends on flaky APIs or fragile setup     |
| **Maintenance Cost**  | Will we have to maintain this?                 | One-and-done, doesn’t change often             | Vendor changes often, breaks silently      |
| **Value vs. Effort**  | Is it worth it?                                | High impact, frequently requested              | Niche, low ROI                             |

---

## Technical Guidelines

> These help keep the project tidy and production-ready.

### 🧠 Code Style

* Use **clear, descriptive names** (e.g., `convertImageToText`, not `imgTxt`)
* Comment your logic if it’s not obvious
* Handle errors — don’t let code crash silently

### 🧼 Clean Contributions

* Don’t change files unrelated to your feature
* Don’t leave behind unused requirements or code
* Don’t introduce huge dependencies (we check image size)
* Use `git status` to review your working tree before you commit

---

## Contribution Types

| Type        | Good Example                                                           |
| ----------- | ---------------------------------------------------------------------- |
| 🐞 Bug Fix  | "Fixes crash when uploading WebP files"                                |
| ⚡ Feature   | "Adds endpoint to replace an expensive api" |
|   📚 Docs | "Improves deployment documentation (e.g., how to host on Netlify, AWS, Vercel, etc.)" |


---

## Final Thoughts 🧘‍♂️

* We're not here to clean up after people — if it's not ready, don't submit it.
* Contributions should be helpful, obvious, and low-maintenance.
* The goal: **make complex tasks simple for no-code users**.

If that excites you, welcome aboard! 🎉

Let’s keep it simple. Let’s keep it clean. Let’s build something useful.
