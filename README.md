# 📘 Full-Stack Test Assignment: Notes App

## Objective

This assignment evaluates your ability to work with unfamiliar technologies — specifically **Spring Boot** and **Flutter** — and build a basic full-stack application. Your primary goal is to demonstrate your ability to learn quickly and apply new concepts.

You are expected to complete this assignment within **two working days**, assuming your current experience is primarily with PHP.

---

## 🧱 Overview

Build a simple "Notes" application consisting of:

### Backend — Java (Spring Boot)

A RESTful API that supports the following operations:

- `GET /notes` — retrieve all notes.
- `POST /notes` — create a new note.
- `PUT /notes/{id}` — update an existing note.
- `DELETE /notes/{id}` — delete a note.

Each `Note` should have the following fields:

| Field      | Type     | Required | Description            |
|------------|----------|----------|------------------------|
| `id`       | UUID or Long | Yes  | Unique identifier      |
| `title`    | String   | Yes      | Note title             |
| `content`  | String   | No       | Note content (optional)|
| `createdAt`| Date     | Yes      | Note creation time     |

Requirements:

- Use an **in-memory database** (e.g., H2).
- Enable **CORS** so the Flutter frontend can access the API.
- No authentication or persistence beyond runtime is required.
- Use Gradle build tool
- Use Spring Boot 3+

---

### Frontend — Flutter

A simple mobile UI that connects to the API and allows the user to:

- View the list of notes.
- Add a new note.
- Edit an existing note.
- Delete a note.

Requirements:

- One screen is sufficient.
- Use plain HTTP for network requests (`http` package is enough).
- State management should be as simple as possible — not required to use any frameworks (e.g., Bloc, Riverpod).
- Visual design is not important — focus on functionality.

---

## 🧪 Deliverables

1. ✅ **Backend source code** (Spring Boot)
2. ✅ **Frontend source code** (Flutter)
3. ✅ A short **README** explaining:
   - How to run both backend and frontend.
   - Any challenges you faced.
   - What resources you used to learn Spring Boot and Flutter.

---

## 🚀 How to Submit

- Upload both backend and frontend projects to a public or private Git repository.
- Send us a link with access instructions (if private).

---

## 📝 Evaluation Criteria

- Ability to understand and work with unfamiliar technologies.
- Functional and correct implementation.
- Code clarity and structure.
- Proper usage of REST conventions.
- Ability to find and apply relevant documentation.

---

## ⏱️ Time Limit

**2 working days** from the time you started implementation of this assignment. Unlimited learning/research time.

Good luck!
