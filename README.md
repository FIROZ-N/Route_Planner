# Route_Planner
A simple single-file Route Planner web app for managing daily travel schedules from Monday to Saturday. Users can add places in order, mark them completed with a dim effect, clear all routes per day, and adjust text size with zoom. All data is saved automatically using localStorage for easy weekly planning.

Route Planner Web App – README

📌 Project Overview

This is a simple, modern, single-file web application designed to help delivery agents, field workers, and travellers plan their daily routes from Monday to Saturday.
Users can manually enter the places they want to cover each day, arrange them in order, and visually track completion using a dim-effect.

Everything is stored in localStorage, so the data remains even after refresh.


---

✨ Features

1. Daily Routes (Mon–Sat)

Each day contains a list of places entered by the user.

User can add unlimited places.

Order is preserved from top to bottom.


2. Completion Marking

Clicking any place will apply a dimmed / completed effect.

Clicking again will un-dim (toggle complete/incomplete).


3. Clear All Routes

Each day has a "Clear All Routes" button to remove all places of that specific day in one click.


4. Zoom In / Zoom Out

Two buttons (+ Zoom and – Zoom) to change text size only.

Helps users with visibility.


5. Data Persistence

All routes and completion status are saved automatically in localStorage.

Refreshing will not delete anything.


6. Simple & Modern UI

Minimal, clean, animated interface.

Roadmap-style vertical route timeline.



---

🛠️ Tech Used

HTML

CSS

JavaScript (Vanilla)

LocalStorage for auto-saving data



---

📂 File Structure

index.html  (single file containing HTML + CSS + JS)


---

📖 How to Use

1. Open the website.


2. Choose a day (Monday–Saturday).


3. Type a place name and click Add.


4. Click any place to mark it completed (dim effect).


5. Use Zoom In / Zoom Out for readability.


6. Use Clear All Routes to remove routes for that selected day.




---

🎯 Purpose

This tool helps field workers manage daily travel schedules efficiently, with:

Clear visual ordering

Completion tracking

One-click clearing

Permanent data storage


Perfect for delivery riders, sales staff, route planners, and weekly repeated tasks.
