# 8. Mod 4 Checkpoint Review

This repository serves as a cumulative checkpoint of all major concepts covered in:

**Mod 4 – Interactive & Data-Driven UI**

---

## Table of Contents

- [Key Concepts](#key-concepts)
- [The Big Idea](#the-big-idea)
- [The Interactive System Flow](#the-interactive-system-flow)
- [Core Topics Review](#core-topics-review)
  - [Forms](#forms)
  - [Validation](#validation)
  - [Promises](#promises)
  - [Fetch API](#fetch-api)
  - [DOM Updates](#dom-updates)
- [Debugging Checklist](#debugging-checklist)
- [Checkpoint Challenge](#checkpoint-challenge)
- [Success Criteria](#success-criteria)

---

## Key Concepts

- **User Intent** — Every interactive feature begins with a user action.
- **Event Handling** — JavaScript listens for and responds to browser events.
- **preventDefault()** — Overrides the browser’s default behavior (like page refresh on form submit).
- **Form Data Extraction** — Accessing input values using `event.target`, `elements`, and `.value`.
- **Fetch API** — Sends HTTP requests and returns a Promise.
- **Promise Chaining** — `.then()` handles success, `.catch()` handles errors.
- **HTTP Methods** — `GET`, `POST`, `PATCH`, `DELETE`.
- **DOM Manipulation** — Updating the UI based on application state.
- **Validation** — Ensuring user input is meaningful and safe before submission.

---

## The Big Idea

Modern web applications are built on a repeatable interaction loop:

> **User → Event → Data → Async → DOM Update**

If you understand this flow, you understand interactive applications.

---

## The Interactive System Flow

### 1. User Action

A user clicks a button or submits a form.

An event is triggered.

---

### 2. Event Listener

JavaScript listens for that event:

```js
form.addEventListener("submit", handleSubmit)
