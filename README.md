# Interrailing-website-for-shortest-path
A web application that helps EuroPass (Interrail Pass) travelers find the shortest and most time-efficient route across Europe using Dijkstra’s algorithm while respecting limited travel days and EuroPass constraints.

# Overview

The EuroPass (Interrail Pass) gives travelers unlimited train rides across Europe, but only within a limited number of travel days. Those days start counting after the first train ride and reset at midnight.

The project allows users to:

Explore train connections between cities

Calculate the shortest path using Dijkstra’s algorithm

Respect the EuroPass midnight rule and day-limit constraint

Visualize an optimal travel plan based on time + day usage


# EuroPass Constraints Implemented

✔ Travel days start after the first train taken
✔ New travel day begins at midnight
✔ If a train crosses midnight, the system increments the day count
✔ Dijkstra only accepts valid edges that don’t exceed the user's available days

🎥 Demo Video: https://drive.google.com/file/d/1AKky3UL1209MrOk6s3B_tEqh5IJUzWl1/view?usp=sharing

📌 Future Improvements

Add map visualization using Leaflet.js

Real-time train API integration

Multi-city planning

Day-pass usage simulation

Mobile-optimized UI
