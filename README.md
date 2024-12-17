# Kirkland - Kirksville Rental Website

Kirksville currently lacks an updated rental website for nearby campus housing, and Kirkland is here to solve this issue. Our platform is designed to connect students with local realtors and landlords, ensuring they have access to the latest housing options. We aim to make the process of finding campus housing easier, faster, and more efficient.

## Features
- **Listings Page:** Browse all available housing options, including apartments and houses.
- **Search by Housing Type:** Easily filter listings to find the perfect fit for your needs.
- **Collaboration with Realtors and Landlords:** Stay updated with newly-opened housing options.

## Tech Stack
Kirkland is built using the **MERN stack** for a modern, full-stack web application:
- **MongoDB:** Database to store and manage housing listings and user data.
- **Express.js:** Backend framework for server-side logic and API development.
- **React.js:** Frontend library for building a responsive and user-friendly interface.
- **Node.js:** Runtime environment for executing server-side JavaScript.

## Getting Started

### Prerequisites
To run this project locally, you will need:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/kirkland.git
   cd kirkland
   ```
2. Install dependencies for both the backend and frontend:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
   Note: Dependencies are listed in the `.gitignore` file and will not be tracked by Git.
3. Set up your MongoDB database and update the configuration file with your connection string.
4. Start the development servers:
   ```bash
   cd backend
   npm run start
   cd ../frontend
   npm start
   ```

### Usage
Navigate to `http://localhost:3000` in your web browser to access the application. Use the search and filter options on the "Listings" page to explore available housing options.
---