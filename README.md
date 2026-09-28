# Patient Health Monitoring & Appointment Management System

A Python console-based application designed to streamline daily clinic operations by digitizing patient records, tracking daily vitals, and managing appointments.

## Key Features
- **Patient Registration & Management**: Add, update, search, delete, and view patient profiles using nested dictionaries[cite: 1].
- **Vitals Tracking**: Record temperature, blood pressure, heart rate, and weight with automated timestamping and history viewing[cite: 1].
- **Appointment Booking System**: Schedule doctor appointments with conflict-detection for double-booked time slots[cite: 1].
- **Data Persistence**: Automatically saves and loads data from local files (`patients.txt`, `vitals.txt`, `appointments.txt`) on startup and exit[cite: 1].
- **Error & Input Validation**: Handles invalid user input, missing file errors, and invalid menu choices using `try-except` blocks[cite: 1].

## Requirements
- Python 3.x (Uses standard built-in libraries only: `json`, `os`, `datetime`)[cite: 1]

## How to Run
```bash
python main.py