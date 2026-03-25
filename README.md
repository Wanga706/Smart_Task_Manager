# 📝 Smart Task Manager.

A simple, responsive task management web application built using **HTML, CSS, and JavaScript**. This project demonstrates core front-end concepts such as DOM manipulation, event handling, and persistent data storage using localStorage.

---

# 📍 Overview

In this capstone project, I used **generative AI prompts** to learn and build a functional web application. The project is about a task manager  that guides others on how to create a task-list allowing them to plan effectively.

---

# 🎯 Project Goal

The goal of this project was to:

- Learn a new/important web development concept using AI  
- Build a simple, working application  
- Document the process clearly for others to follow  
- Reflect on how AI improved learning and productivity  

---

# 🏷️ Title & Objective

## Title:
**Building a Smart Task Manager with Vanilla JavaScript – A Beginner’s Guide**

## Objective:
To build a task manager web app that allows users to:
- Add tasks  
- Mark tasks as complete  
- Delete tasks  
- Filter tasks  
- Save tasks using localStorage  

## Why I chose this technology:
I chose **Vanilla JavaScript** to strengthen my understanding of core web development concepts before moving to advanced frameworks.

## End Goal:
To create a functional and user-friendly task manager that persists data even after page refresh.

---

# ⚡ Quick Summary of the Technology

**What is Vanilla JavaScript?**  
It is the use of plain JavaScript without frameworks or libraries.

## 📌 Where it is used:
- Interactive websites  
- Frontend applications  
- Browser-based tools  

## 🌍 Real-world examples:
- To-do list apps  
- Calculators  
- Dashboards  

---

# 💻 System Requirements

- OS: Windows / Linux / Mac  
- Browser: Chrome / Firefox  
- Code Editor: VS Code  
- Git (optional, for version control)  

---

# ⚙️ Installation & Setup Instructions

## Step 1: Create Project Folder
```bash
mkdir task-manager
cd task-manager
```

📌 Description

This app allows users to manage daily tasks and saves them in the browser.```


💡 Sample Code
```
function addTask() {
  const input = document.getElementById("taskInput");
  const text = input.value.trim();

  if (text === "") return;

  tasks.push({ text, completed: false });
  localStorage.setItem("tasks", JSON.stringify(tasks));
}
```

## 📁 Project Structure
task-manager/
│── index.html
│── style.css
│── script.js

## 🚀 Features
✅ Add tasks
✅ Mark tasks as completed
✅ Delete tasks
✅ Filter tasks (All / Completed / Pending)
✅ Persistent storage using localStorage
✅ Responsive design
