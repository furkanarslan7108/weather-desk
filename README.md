# Weather Desk

A simple **Python + PyQt6 desktop application** that shows weather information, a calendar, and (eventually) a per-day to-do list.  
This project is designed to give hands-on experience with **OOP design**, **UI/UX development**, and **API integration** using `requests`.

---

## 📖 Project Overview

This application will evolve in several iterations:

1. **MVP** – Display weather for a selected city.
2. **User Interaction** – Add city input, error handling, and UI improvements.
3. **Forecast + Calendar** – Show multi-day forecast and a basic monthly calendar.
4. **To-Do List** – Add a simple day-specific task tracker.
5. **Polish & Testing** – Refine UI, add icons, write docstrings, and minimal unit tests.

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **UI Framework:** PyQt6
- **HTTP Requests:** `requests`
- **Data Storage:** Local JSON (for to-do list)
- **Version Control:** Git + GitHub (PR-based workflow)

---

## 📂 Project Structure (Planned)

weather_calendar_app/
│
├── main.py # Entry point for the application
├── services/
│ └── weather_service.py # Handles API calls
├── ui/
│ ├── main_window.py # Main PyQt window
│ ├── weather_view.py # UI for displaying weather data
│ └── calendar_view.py # UI for displaying calendar
├── models/
│ └── todo_model.py # Manages per-day to-do items
└── README.md

---

## 🚀 Getting Started

### Prerequisites
Make sure you have:
- Python 3.10+ installed
- `pip` installed

### Installation

```bash
git clone https://github.com/<YOUR_USERNAME>/weather-calendar-app.git
cd weather-calendar-app
pip install -r requirements.txt
```

Running the App

```python
python main.py
```
