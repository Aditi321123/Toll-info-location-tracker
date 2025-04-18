# Toll-info-location-tracker
Got it! Here's the updated GitHub project description reflecting that your system **calculates toll tax based on distance traveled**, not just detecting nearby toll plazas:

---

# Toll Info Location Tracking System

A simple yet powerful web application that **calculates toll tax based on the distance traveled** using browser-based geolocation. This system continuously tracks the user's real-time location, stores it, and computes the total toll amount by comparing the distance covered against predefined toll rules — helping users manage travel expenses more efficiently.

---

## Project Overview

This project demonstrates a real-time location-based toll tax calculator built using:
- Frontend: HTML, CSS, JavaScript (Geolocation API)
- Backend: Python
- Database: SQLite

The application captures the user's GPS coordinates through the browser, sends the data to a Python backend, stores it in a local database, and calculates toll charges based on how far the user has traveled.

---

## Key Features

- Live Location Tracking using the browser’s Geolocation API  
- Backend Processing with Python to handle location storage and toll logic  
- SQLite Database-for recording coordinates with timestamps  
- Toll Tax Calculation based on distance traveled  
- No Installation Needed – just open the app in a browser!

---

## How It Works

1. User opens the web app and grants location permission.
2. The app periodically sends updated coordinates to the backend.
3. The backend logs the data and calculates distance using GPS points.
4. Based on distance and predefined toll rules, the system estimates the toll tax.

---

## Future Enhancements

- Google Maps integration for live route visualization
- Android/iOS app version
- Integration with FASTag or official toll data sources
- Dashboard to track trip history, routes, and expenses

---

## Project Structure

```bash
toll_app/
├── index.html           # Frontend UI with location tracking
├── main.py              # Python backend script
├── location.db          # SQLite database storing location data
├── toll_data.csv        # Rules/data for toll calculation
```
