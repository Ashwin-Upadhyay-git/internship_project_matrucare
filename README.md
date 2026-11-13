# MATRUCARE AI

A production-oriented hackathon registration portal for MatruCare AI.

## Overview
This project delivers a complete full-stack registration experience for a technology hackathon, combining a React + Vite frontend with an Express + MongoDB backend. It includes user authentication, OTP verification, secure session handling, registration workflows, email notifications, and responsive UI.

## Features
- Public landing page with event overview and CTAs
- Signup and OTP verification flow
- Secure login with JWT-based authentication
- Protected dashboard with registration status
- Hackathon registration with dynamic team member management
- Contact form with validation and email handling
- MongoDB persistence with Mongoose models
- Responsive Tailwind UI and accessible navigation
- Security middleware including Helmet, CORS, rate limiting, and validation

## Tech Stack
- Frontend: React, Vite, Tailwind CSS, React Router DOM
- Backend: Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt, Nodemailer
- Validation: Zod
- Testing: Vitest, Supertest

## Repo Structure
- client/: React frontend
- server/: Express backend and tests
- docs/: API and deployment docs

## Installation
1. Clone the repository.
2. Install root dependencies: `npm install`
3. Set up environment files in `client/.env.example` and `server/.env.example`.
4. Start the backend: `npm run dev:server`
5. Start the frontend: `npm run dev`

## Documentation
See the docs folder for detailed API and deployment guidance.

## Notes
This repository was initialized from an empty state and includes implementation-ready architecture as a professional starting point. Real email credentials, MongoDB credentials, and deployment URLs must be configured before running in a live environment.
