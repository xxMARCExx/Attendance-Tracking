# Attendance-Tracking


# Attendance Tracking Agent

This is a FastAPI-based agent that processes uploaded attendance files (.csv or .xlsx), flags students with multiple absences, and generates a summary using GPT-4o.

## Features

- Upload attendance data securely via an API
- Flag students with ≥ 3 absences
- Auto-generate a summary report with OpenAI GPT-4o
- Designed for integration with academic systems

## Deployment Instructions (Render)

1. Create a new **Web Service** on [Render](https://render.com).
2. Connect this repo or upload the files.
3. Set the build and start commands:

   **Build Command**
