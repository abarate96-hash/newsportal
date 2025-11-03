# Backend Development for NewsPortal

## Overview
Create a Node.js Express backend that allows easy content uploading, stores data locally in JSON files, provides APIs for fetching/uploading content, serves the static frontend, and updates the frontend to load content dynamically.

## Steps to Complete

### 1. Set Up Backend Directory Structure
- [ ] Create `backend/` directory
- [ ] Create `backend/data/` subdirectory for JSON files
- [ ] Create `backend/server.js` for the Express server
- [ ] Create `backend/package.json` for dependencies

### 2. Initialize JSON Data Files
- [ ] Extract hardcoded news data from index.html and create `backend/data/news.json`
- [ ] Extract hardcoded podcasts data and create `backend/data/podcasts.json`
- [ ] Extract hardcoded videos data and create `backend/data/videos.json`
- [ ] Extract hardcoded trending data and create `backend/data/trending.json`

### 3. Implement Express Server and Routes
- [ ] Set up Express server in `server.js` with CORS and JSON parsing
- [ ] Implement GET routes: `/api/news`, `/api/podcasts`, `/api/videos`, `/api/trending`
- [ ] Implement POST routes: `/api/news`, `/api/podcasts`, `/api/videos`, `/api/trending` for uploading content
- [ ] Add static file serving for the frontend (serve `index.html` and assets from root directory)

### 4. Update Frontend (index.html)
- [ ] Remove hardcoded news, podcasts, videos, and trending data from HTML
- [ ] Add JavaScript functions to fetch data from APIs on page load
- [ ] Update DOM manipulation to dynamically populate content sections
- [ ] Ensure interactive functions (readArticle, playPodcast, etc.) work with dynamic data

### 5. Install Dependencies and Test
- [ ] Install Express and CORS via npm
- [ ] Test server startup and API endpoints
- [ ] Verify frontend loads and displays dynamic content
- [ ] Test POST endpoints for uploading new content

### 6. Documentation and Instructions
- [ ] Provide README.md with setup and usage instructions
- [ ] Include examples for uploading content via API calls
- [ ] Document API endpoints and data formats

## Completion Criteria
- Backend server runs successfully
- Frontend loads dynamic content from APIs
- POST endpoints allow easy content uploading
- All original functionality preserved
- Data persists in local JSON files
