# VOICE: Civic Issue Reporting Platform

## Purpose
VOICE is a web-based civic issue reporting platform that empowers citizens to raise, discuss, and track local civic issues in their communities. It acts as a bridge between the public and concerned authorities, enabling transparent and collaborative problem-solving.

## Features
- **Issue Reporting:** Users can report new community issues with details, images, location, and assign a priority.
- **Authentication:** Secure user registration and login (including Google OAuth support).
- **Browse & Filter Issues:** Issues can be browsed, filtered by area/pincode, and sorted by recency or popularity.
- **Upvoting:** Community-driven upvote system to highlight urgent issues. Undo allowed for upvotes within a minute.
- **Commenting:** Discuss issues with comments (for registered users).
- **Admin Dashboard:** Administrative capabilities to manage issues, users, and track overall analytics.
- **Image Uploads:** Attach photos to better describe issues (AWS S3 integration).
- **Analytics:** Summaries and statistics (number of issues, status, users, etc.)
- **Mobile-friendly UI:** Clean, modern frontend optimized for desktop and mobile use.

## Tech Stack
### Backend
- **Node.js** + **Express.js**: REST API server
- **MongoDB** (via Mongoose): Database for users, issues, comments, etc.
- **JWT Authentication** (with passport, Google OAuth)
- **Image uploads**: Multer & AWS S3 SDK
- Security: Helmet, CORS, express-rate-limit

### Frontend
- **React** (Vite-based, Hooks & Context API)
- **Material UI (MUI)** and **TailwindCSS**: Modern responsive design
- **React Router** for navigation
- **Axios** for API communication
- **React Hot Toast** for notifications
- **Framer Motion** for animations

## Folder Structure
```
voice/
  backend/      # Node/Express backend, all API code
  frontend/     # React client app
```

## Getting Started
Check `setup.md` for local environment setup and deployment instructions.

---

For more, see the respective `backend/` or `frontend/` folders and the main project `README.md`.
