# AI Career Assistance Platform

This is a React-based web application designed to help users upload their resumes, analyze job descriptions, track job applications, and practice mock interviews using AI.

## 🚀 Features

- **Authentication:** Secure user login and registration flows.

  <img width="1908" height="923" alt="image" src="https://github.com/user-attachments/assets/4ff6b8c1-bb3e-4dc4-a640-3d465d5d0681" />

- **Dashboard:** An overview of your career preparation progress.

  <img width="1919" height="929" alt="image" src="https://github.com/user-attachments/assets/46240c23-ab9c-416a-b0d8-f1cb2648f913" />

- **Resume Parsing:** Upload your PDF resume for AI-driven structure extraction.

  <img width="1919" height="926" alt="image" src="https://github.com/user-attachments/assets/91314044-dfdb-456f-b84d-1e6e8552c38b" />

- **Job Analysis:** Compare your resume against Job Descriptions (JDs) to identify skill gaps.

  <img width="1919" height="927" alt="image" src="https://github.com/user-attachments/assets/da501a61-0e56-4bea-9efa-7dd557edd3bd" />

- **AI Mock Interviews:** Participate in dynamic, role-playing mock interviews with an AI, tailored to your specific resume and the role you're applying for.

  <img width="1913" height="591" alt="image" src="https://github.com/user-attachments/assets/ecbbbea2-91f6-4d97-9287-9050e4827c00" />

- **Job Tracker:** A kanban-style or list-style tracker to manage your active job applications.

  <img width="1919" height="806" alt="image" src="https://github.com/user-attachments/assets/192662a7-dc54-47eb-b33e-3cdb3383779a" />

- **Dark/Light Mode:** Full theming support explicitly built-in.

## 🛠️ Tech Stack

- **React 18**
- **Vite** (Build Tool)
- **Tailwind CSS & PostCSS** (Styling)
- **React Router DOM** (Client-side routing)

## 📦 Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn

### Installation

1. Clone this repository and navigate to the frontend directory:
   ```bash
   cd resume-review-FE
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment variables. Make sure your `.env` or `.env.local` points to your running backend server (e.g., `VITE_API_URL=http://localhost:5000/api`).

### Available Scripts

In the project directory, you can run:

- `npm start` OR `npm run dev` (Depending on your `package.json` config, usually mapped to `vite`)
  Runs the app in development mode. Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

- `npm run build`
  Builds the app for production to the `dist` folder. It correctly bundles React in production mode and optimizes the build for the best performance.

- `npm run preview`
  Locally preview the production build.

## 📂 Project Structure

- `/src/pages` - Contains the main route views (`Dashboard.jsx`, `MockInterview.jsx`, `ResumeUpload.jsx`, etc.)
- `/src/components` - Reusable UI components.
- `/src/contexts` - React contexts (e.g., `AuthContext.js` for handling authentication state).
