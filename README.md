# Smart-study-planer-

## Overview
The Smart Study Planner is a web application designed to help students efficiently schedule and manage their study tasks. Utilizing React for the front end and Firebase for backend storage, the application dynamically organizes tasks based on deadlines and priorities.

## Features
- Task Input & Scheduling: Add tasks, set due dates, and categorize them by priority.
- Smart Scheduling: Get optimized task order suggestions based on urgency and workload.
- Progress Tracking: Track completed and pending tasks dynamically.
- Drag & Drop Functionality: Reorder tasks easily.
- Dark Mode: Switch between light and dark themes.

## Technology Stack
- Frontend: React (JavaScript), Tailwind CSS
- State Management: React hooks (useState, useEffect)
- Data Storage: Firebase Firestore
- Data Handling: Luxon.js or JavaScript’s built-in Date() functions
- Deployment: Vercel or Netlify

## Getting Started

### Prerequisites
- Node.js
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-study-planner.git
   cd smart-study-planner
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Configure Firebase:
   - Replace the placeholder values in `src/firebase.js` with your Firebase project's configuration.

4. Start the development server:
   ```bash
   npm start
   # or
   yarn start
   ```

5. Open your browser and navigate to `http://localhost:3000`.

## Deployment

To deploy the application, you can use Vercel or Netlify.

### Vercel

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

### Netlify

1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```

2. Deploy:
   ```bash
   netlify deploy
   ```

## License
This project is licensed under the MIT License.
