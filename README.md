# Trivia-Guide: Interactive Web-Based Knowledge Assessment Platform

## Executive Summary

This project features the development of a functional, responsive web application designed for interactive trivia and knowledge assessment. Utilizing HTML5, CSS3, and modern JavaScript, the system integrates dynamic DOM manipulation with a robust state management algorithm for question rendering and score tracking.

The software architecture was designed under **User-Centered Design (UCD)** principles, prioritizing interface accessibility, responsive behavior across devices, and deterministic logic execution for the quiz state.

## Technical Stack

* **Core Structure:** HTML5 (Semantic markup and accessibility).
* **Styling & UI:** CSS3 (Flexbox/Grid architecture, responsive media queries).
* **Logic & Execution:** JavaScript ES6+ (Object-Oriented/Functional paradigms).
* **Environment:** Modern Web Browsers (Client-side execution).

---

## System Architecture & Logic

The system operates via a structured execution flow to ensure deterministic behavior during user interactions:

1. **State Management Module:** Prior to rendering, the system initializes variables to track the current question index, accumulated score, and selected categories.
2. **Dynamic Rendering Engine:** Fetches the question data and multiple-choice options, dynamically injecting them into the DOM without requiring a page reload.
3. **Evaluation & HMI Module:** Provides real-time validation of user inputs. It compares the selected option against the correct answer matrix, updating the Human-Machine Interface (HMI) with immediate visual feedback.

---

## Evaluation & Interaction Matrix

To ensure a seamless user experience, the following event matrix was implemented for the game's logic:

| Detected Event | System Action | Visual Indicator |
| :--- | :--- | :--- |
| **Correct Answer Selected** | Increment score variable by 1 | Green highlight on selected UI node |
| **Incorrect Answer Selected** | Maintain current score | Red highlight on selected UI node |
| **Quiz Completion** | Calculate final performance percentage | Results dashboard displayed on screen |

---

## File Architecture (Directory Mapping)

| Component | Path | Function |
| :--- | :--- | :--- |
| **Main Entry** | `index.html` | Application skeleton and primary UI container |
| **Styles** | `assets/css/style.css` | UI/UX visual formatting and responsiveness |
| **Logic** | `assets/js/app.js` | Core execution, event listeners, and state control |
| **Static Assets** | `assets/img/` | Graphical assets, icons, and demonstration files |

---

## How to Run

1. Clone the repository to your local machine using:
   `git clone https://github.com/HJLeslye/Trivia-Guide.git`
2. Navigate to the project directory.
3. Open the `index.html` file directly in any modern web browser. No local server or dependencies are required for execution.

---

## Contact Details

> **Leslye Hernández Jiménez**
> *IT & Communications Engineering*
>
> **LinkedIn**: [View Profile](https://www.linkedin.com/in/leslye-hernandez-jimenez)
> **Email**: [hdezj.leslye@gmail.com](mailto:hdezj.leslye@gmail.com)

