# FocusHub

> A professional, local-first productivity operating system designed for deep work, structured planning, and distraction-free execution.

FocusHub is a lightweight browser application that combines task management, time blocking, Pomodoro sessions, productivity analytics, and daily planning into a single workspace. Built entirely with Vanilla JavaScript, it requires no installation, no build tools, and no external frameworks.

---

## Overview

Modern productivity tools often separate planning, task management, focus timers, and daily metrics into multiple applications. FocusHub brings these workflows together in one minimal, responsive interface while keeping all data stored locally in your browser.

Designed around speed, clarity, and zero-friction interaction, the application launches instantly and works without any backend infrastructure.

---

# Features

## Workspace Experience

### Adaptive Sidebar

- Expandable and collapsible navigation
- Maximizes workspace when collapsed
- FocusHub logo becomes the restore control
- Smooth layout transitions

### Dynamic Ambient Background

The interface automatically changes throughout the day.

- Morning
- Afternoon
- Evening
- Night

This creates a subtle visual reflection of your current work cycle.

---

## Task Management

Organize and prioritize work efficiently.

Features include:

- Add, edit and delete tasks
- Priority levels
  - High
  - Medium
  - Low
- Automatic priority sorting
- Completion tracking
- Persistent local storage
- Visual completion indicators

---

## Daily Goals

Track measurable daily objectives.

Includes:

- Custom daily targets
- Live progress calculation
- Percentage completion
- Progress visualization
- Automatic updates

---

## Custom Time Planner

Build structured schedules without relying on native browser controls.

Features:

- Custom time picker wheels
- Smooth dropdown selection
- Chronological planning
- Add and remove schedule blocks
- Persistent planner state

---

## Pomodoro Focus Engine

Highly configurable focus sessions.

Supports:

- Adjustable work duration
- Short break duration
- Long break duration
- Session count
- Incremental + / - controls
- Local persistence

---

## Weather Timeline

Real-time weather diagnostics powered by Open-Meteo.

Displays:

- Current conditions
- Upcoming 6-hour forecast
- Temperature
- Weather indicators

Uses:

- Browser Geolocation API
- Open-Meteo API

---

## Insights Hub

A dedicated space for productivity knowledge.

Features include:

- Fetch focus insights from APIs
- Save favorite insights
- Local archive
- Offline persistence

---

## Celebration System

FocusHub automatically celebrates important achievements.

Triggers include:

- Completing every task
- Achieving 100% daily goals

---

# Project Structure

```text
FocusHub/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

| File | Description |
|-------|-------------|
| `index.html` | Application layout and semantic structure |
| `style.css` | Complete styling system, themes and responsive UI |
| `script.js` | Business logic, local storage, timers and application state |

---

# Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- Local Storage API
- Geolocation API
- Open-Meteo API

No frameworks.

No build tools.

No package managers.

No dependencies.

---

# Local Storage

FocusHub follows a **local-first architecture**.

The following data is stored inside your browser:

- Tasks
- Planner entries
- Pomodoro settings
- Daily goals
- Theme preference
- Saved insights
- Application preferences

No information is transmitted to external servers except weather requests.

---

# Live Demo

Experience FocusHub directly in your browser.

**Live Application**

🔗 **https://your-domain.com**

No installation, registration, or setup required.

Simply open the link in any modern browser and start organizing your tasks, planning your day, and tracking your focus sessions.

---

## Browser Support

FocusHub works on all modern browsers, including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

For the best experience, use the latest version of your preferred browser.

---

## Permissions

Some features require optional browser permissions.

| Permission | Purpose |
|------------|---------|
| Location | Displays local weather forecasts using the Open-Meteo API |
| Local Storage | Saves tasks, planner data, Pomodoro settings, goals, and preferences directly in your browser |

If location access is denied, the weather widget will be disabled while the rest of the application continues to function normally.

# Weather API

FocusHub uses the free **Open-Meteo API**.

The weather module requires:

- Internet connection
- Browser geolocation permission

If location access is denied, the weather widget will remain unavailable while the rest of the application continues to function normally.

---

# Design Philosophy

FocusHub is built around five principles.

### Minimal

Only essential information is displayed.

### Local First

Your data belongs to you.

### Fast

No frameworks.
No unnecessary JavaScript.
Instant startup.

### Distraction Free

A clean interface that prioritizes execution over configuration.

### Accessible

Simple controls with high usability and keyboard-friendly interactions.

---

# Performance

- Lightweight
- Fast initial load
- Zero runtime dependencies
- Instant persistence
- Responsive layout
- Offline-friendly (excluding weather data)

---

# Roadmap

Planned improvements include:

- Calendar integration
- Drag-and-drop task organization
- Keyboard shortcuts
- Weekly analytics dashboard
- Recurring tasks
- Export and import backups
- Markdown notes
- Focus statistics
- Productivity heatmaps
- Notification reminders
- PWA support
- Multi-theme customization

---

# Contributing

Contributions are welcome.

If you would like to improve FocusHub:

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push the branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

# Author

Developed by **Akshay Dhanraj Kurve**

If you found this project useful, consider giving it a ⭐ on GitHub.
