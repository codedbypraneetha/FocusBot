# FocusBot

## Overview

FocusBot is a productivity assistant built using UiPath RPA. It helps users stay focused during study sessions by displaying daily tasks, monitoring distractions, logging interruptions, and generating an end-of-day report.

The project demonstrates workflow automation, Excel integration, UI Automation, and process orchestration using UiPath.

---

## Features

* Displays a morning briefing with the day's tasks
* Reads tasks from an Excel workbook
* Monitors the active application window continuously
* Detects distracting websites and applications
* Displays an alert when a distraction is detected
* Logs distraction details into Excel with timestamp
* Generates an end-of-day report
* Modular workflow design for easy maintenance

---

## Project Structure

```
FocusBot
│
├── MAIN
│   ├── Morning.xaml
│   ├── FocusBot_ActiveWindow.xaml
│   └── EndOfDayReport.xaml
│
├── project.json
└── README.md
```

---

## Technologies Used

* UiPath Studio (Windows Project)
* UiPath System Activities
* UiPath Excel Activities
* UiPath UI Automation Activities
* Microsoft Excel

---

## Workflow Description

### Morning.xaml

* Reads tasks from Excel
* Displays a morning task briefing

### FocusBot_ActiveWindow.xaml

* Continuously monitors the active window
* Detects distracting applications and websites
* Shows an alert if a distraction is detected
* Logs distraction details into Excel

### EndOfDayReport.xaml

* Reads the distraction log
* Generates a summary of the study session

---

## Excel Files

The project uses an Excel workbook to:

* Store daily tasks
* Maintain distraction logs
* Generate session reports

---

## Future Improvements

* Pomodoro timer
* Website auto-blocking
* Productivity score calculation
* Weekly analytics dashboard
* Calendar integration
* Custom distraction list
* Email daily reports

---

## Author

Praneetha Vanamala
