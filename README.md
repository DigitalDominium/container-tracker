# Container Tracker

A React-based web application for tracking containers using drag-and-drop and OCR scanning with Tesseract.js. Users can enter container numbers, scan them via camera, upload a blueprint, and assign containers to bays.

## Features
- Add and remove containers
- Realtime camera scanning for container numbers
- Drag-and-drop to assign containers to bays
- Responsive design for mobile and desktop
- Blueprint image upload for bay visualization

## Setup
1. Clone the repository: `git clone https://github.com/your-username/container-tracker.git`
2. Install dependencies: `npm install`
3. Build the app: `npm run build`
4. Serve locally: `npm start`

## Deployment
Deployed on Render as a Static Site. Build command: `npm install && npm run build`. Publish directory: `build`.

## Dependencies
- React 18.2.0
- react-dnd 16.0.1
- react-dnd-html5-backend 16.0.1
- tesseract.js 5.1.0
