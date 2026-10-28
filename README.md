# DOSSL Practical Project - Study Planner

This project is a practical web development assignment built to help students manage their study schedule efficiently. The application allows users to add study topics, set duration and target dates, record notes, track completion status, and search items quickly.

## Project Overview

The Study Planner is a lightweight front-end application designed for daily academic planning. It demonstrates core web development concepts such as DOM manipulation, event handling, form validation, responsive UI design, and browser storage.

It is useful for students who want to:

- organize topics for exam preparation
- manage deadlines and study durations
- track which subjects are completed or pending
- keep short study notes in one place
- review progress through a clean dashboard

## Features

- Add new study topics
- Set study duration and target date
- Add personal notes for each topic
- Mark entries as completed or pending
- Search topics by name, notes, or status
- Delete or update study entries
- Toggle between light and dark theme
- Responsive design for desktop and smaller screens

## Technologies Used

- HTML5
- CSS3
- JavaScript
- LocalStorage for theme persistence
- Jest and JSDOM for testing

## Project Structure

```text
DOSSL-Practical/
├── Code/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   ├── package.json
│   ├── build.js
│   ├── Dockerfile
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── Jenkinsfile
│   └── README.md
├── Screenshots/
│   ├── Assignment1/
│   ├── Assignment2/
│   ├── Assignment3/
│   ├── Assignment4/
│   ├── Assignment5/
│   ├── Assignment6/
│   ├── Assignment7/
│   └── Assignment8/
├── test/
│   └── test.js
└── README.md
```

## How to Run

1. Open the project folder.
2. Go to the `Code` directory.
3. Open `index.html` in a browser, or run a local server:

```bash
cd Code
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Testing

The project includes basic tests for core file existence and application behavior.

```bash
cd Code
npm install
npm test
```

## Conclusion

This practical project demonstrates the creation of a student-friendly planning tool using core front-end web technologies. It is a strong example of how a simple project can combine user interaction, data management, and professional documentation in one application.
