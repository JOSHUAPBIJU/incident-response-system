# **Impact of UI Design on Cybersecurity Incident Reporting: A Form vs. Chatbot Comparison**

This project is developed by [Joyel Porunnedath Biju](https://github.com/joyelpbiju) and [Joshua Porunnedath Biju](https://github.com/JOSHUAPBIJU) as part of an **Interactive Systems** project at **Schmalkalden University of Applied Sciences**.

![License](https://img.shields.io/badge/license-MIT-green) ![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen) ![Status](https://img.shields.io/badge/status-active-brightgreen)

---

## **Project Overview**

Cybersecurity incidents pose a growing challenge for organizations, requiring effective reporting mechanisms to ensure timely responses. This project evaluates two different **User Interface (UI) approaches** for incident reporting:

- **Prototype A:** A traditional **multi-step form-based** UI.
- **Prototype B:** An **interactive chatbot-based** UI that provides a conversational experience.

The research aims to analyze how **interface design impacts user efficiency, error rates, and preference** in cybersecurity reporting. A comparative study is conducted, testing user performance and collecting usability feedback through a **System Usability Scale (SUS) questionnaire**.

---
## **Features**

- **Prototype A (Form-Based UI):**
  - Multi-step structured form with manual data entry.
  - Progress indicator to track completion.
  - Traditional step-by-step interaction.

- **Prototype B (Chatbot-Based UI):**
  - Conversational chatbot for guided incident reporting.
  - Users can select predefined responses or enter short replies.
  - Single scrolling interface for smooth workflow.

- **Research & Data Analysis:**
  - Performance metrics: **Task completion time & error rate** comparison.
  - User experience evaluation using **SUS questionnaire**.
  - Statistical analysis via a **paired t-test**.

---

## **Technologies Used**

### **Frontend**
- **HTML5** – UI structuring.
- **CSS** – Styling and responsive design.
- **JavaScript** – Dynamic interactions.

### **Backend**
- **Python (Flask)** – Web framework for handling requests.
- **SQLite** – Database for storing task completion time and error counts.

---
## **Study Methodology**

- **Participants:** 30 users (aged 20-30, with 43.3% female participation).
- **Metrics Recorded:**
  - **Task Completion Time:** Time taken to report an incident.
  - **Errors:** Number of mistakes while entering information.
  - **User Preference:** Rated via **SUS questionnaire**.
- **Hypotheses Tested:**
  1. Users will make **fewer errors** in Prototype B than in Prototype A.
  2. Users will complete tasks **faster** in Prototype B than in Prototype A.
  3. Users will **prefer Prototype B** over Prototype A in usability.

---
## **How to Run the Project**

### **Prerequisites**
1. Install Python **(version 3.8 or later)**.
2. Install `pip` for managing Python packages.

### **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/joyelpbiju/incident-response-system.git
   cd incident-response-system
   ```
2. Run the Flask app:
   ```bash
   python src/app.py
   ```
3. Open the web application in your browser:
   ```
   http://127.0.0.1:5000
   ```

---
## **Results Summary**
- **Prototype B (Chatbot UI)** outperformed **Prototype A (Form UI)** in **task efficiency and error reduction**.
- **SUS Scores:**
  - **Prototype A:** 42.16 (**Awful**).
  - **Prototype B:** 89.00 (**Excellent**).
- **Statistical Significance:** The differences in task completion time and errors were highly significant (**p < 0.00001**).
- **Conclusion:** Users **preferred the chatbot UI**, which provided a **faster, structured, and user-friendly** experience compared to the traditional form.

---
