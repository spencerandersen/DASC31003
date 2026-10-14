# DASC31003


# Apex Hoops Manager

A pure client side basketball tournament bracket simulation and franchise tycoon built into a single static file.

## Core Features

* Sixteen team single elimination bracket with live seed tracking
* Tactical engine calculating pace, offensive efficiency, defensive stops, and roster fatigue
* Interactive match center featuring animated quarter by quarter live tickers and box scores
* Front office economy awarding cash for playoff advancement
* Facility upgrades including training camps, sports science recovery, and scouting reports
* Browser state persistence via localStorage across sessions and seasons

## Architecture

* Single file architecture containing markup, logic, and presentation in index.html
* Zero backend dependencies running entirely in browser memory
* CDN integrations via Tailwind CSS, Lucide icons, and Canvas Confetti

## Google Cloud Storage Deployment

1. Create a storage bucket configured for public website hosting.
2. Upload index.html to the bucket root:
`gcloud storage cp index.html gs://YOUR_BUCKET_NAME`
3. Assign Storage Object Viewer access to allUsers.
4. Set the default index page to index.html.

## Local Run

Launch index.html directly inside any modern web browser. No local development server or build step required.