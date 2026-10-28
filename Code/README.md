# Study Planner

A practical web application for managing study topics, deadlines, and academic progress. This project is designed as a student-friendly task manager where users can add study subjects, set durations, record notes, and track which topics are completed.

## Practical Project Overview

This project was developed as part of a practical assignment to demonstrate front-end web development using HTML, CSS, and JavaScript. The application focuses on real-world student needs such as tracking assignments, preparing for exams, and organizing daily learning tasks in one place.

## Features

- Add study topics with duration and target date
- Save notes for each topic
- Mark tasks as pending or completed
- Search topics quickly by name, notes, or status
- Delete tasks when they are no longer needed
- Change the interface between light and dark theme
- Store data locally in the browser

## Technologies Used

- HTML5
- CSS3
- JavaScript
- LocalStorage
- Jest and JSDOM for testing

## Project Structure

```text
Code/
├── index.html
├── style.css
├── script.js
├── package.json
├── build.js
├── Dockerfile
├── deployment.yaml
├── service.yaml
├── Jenkinsfile
├── README.md
└── ...
```

## Run the Project

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Run with a local server

```bash
cd Code
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Testing

```bash
cd Code
npm install
npm test
```

## Screenshot Gallery

The screenshots below show the practical implementation and progress of the project.

### Main application interface

![Study Planner dashboard](../Screenshots/Assignment3/Manual%20build.png)

### Build and deployment workflow

![Study Planner build output](../Screenshots/Assignment3/Successful%20build.png)

### Assignment progress examples

![Progress screenshot 1](../Screenshots/Assignment4/Screenshot%202026-10-27%20093432.png)
![Progress screenshot 2](../Screenshots/Assignment5/Screenshot%202026-09-15%20144128.png)

## Summary

This Study Planner project is a practical and useful web application that demonstrates how a simple interface can help students organize learning tasks effectively. It combines user-friendly interaction, responsive design, and practical project documentation in one complete solution.