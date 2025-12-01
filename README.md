1. Overview 🌍

waySAFE is a smart safety guidance system that analyzes surroundings, detects risks, and recommends safer routes. Powered by AI and multi agent reasoning, waySAFE helps users feel confident and protected during every journey.

2. Key Features ⚡

Smart safety scoring
Uses lighting, crowd levels, time of day, historical incidents, and environmental cues.

Risk detection agent
Flags unsafe zones such as dimly lit paths, isolated areas, or suspicious patterns.

Route recommendation agent
Suggests safer alternatives with clear reasoning and context.

Timeline and incident memory
Stores previous decisions to improve guidance over time.

Modern dashboard UI
Clean, intuitive Vite React dashboard showing maps, scores, logs, and agent insights.

3. System Architecture 🏗️

Frontend (waysafe dashboard)
Built with React, Tailwind, shadcn, and Vite for fast rendering and smooth interactions.

AI Agents Layer
Safety scorer, risk analyzer, and decision agent work together to produce final recommendations.

Backend computation
Python notebook logic contains the data processing, formulas, and agent workflows.

Data & logging
Basic in memory logs help track reasoning steps and decision flow.

4. How It Works 🔍

User provides a location or route.

The safety agent computes a safety baseline score.

The risk detection agent scans for hazards.

The recommendation agent generates a safer route.

Dashboard visualizes the result with charts, maps, and logs.

5. Project Structure 📂

implementation.ipynb
Core safety logic, formulas, and agent reasoning.

waysafe-dashboard
React interface to display analysis, metrics, and route insights.

Contains:

components

pages

api layer

charts

theme and layout files

routing

UI elements (shadcn)

6. Installation & Setup ⚙️
Frontend
cd waysafe-dashboard
npm install
npm run dev

Backend

Open implementation.ipynb in Jupyter or VSCode and run all cells.

7. Future Enhancements 🌱

Real time GPS and live movement tracking

Integration with city open data APIs

Notification alerts for nearby incidents

Multi city safety scoring maps

Full mobile app using React Native Expo

8. Credits 🤝

Built with care, clarity, and purpose for the waySAFE project.
Designed to protect every step and empower users with smarter safety decisions.
