# Reelfy

A modern React application to search for movies, view trending titles, and track popular searches. Built with Vite, Tailwind CSS, and Appwrite for trending analytics.
[Reelfy](https://reelfy.netlify.app/)

## Features

- 🔍 **Search Movies:** Instantly search through thousands of movies using The Movie Database (TMDb) API.
- 📈 **Trending Movies:** Displays the top 5 trending movies based on user search activity, powered by Appwrite.
- 🎬 **Movie Details:** View movie posters, ratings, release years, and languages.
- ⚡ **Fast & Responsive:** Built with Vite and styled using Tailwind CSS for a seamless user experience.
- 🌀 **Loading Spinner:** Visual feedback while fetching data.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/movie-search-app.git
   cd movie-search-app
   
Install dependencies:

Set up environment variables:

Create a .env.local file in the root directory with the following content (replace with your own keys if needed):

Running the App
Start the development server:

Open http://localhost:5173 in your browser.

Building for Production
Linting
Project Structure
src/Components/ – React components (MovieCard, Search, Spinner)
src/appwrite.js – Appwrite integration for trending analytics
src/App.jsx – Main application logic
src/index.css – Tailwind CSS and custom styles
Environment Variables
See .env.local for required variables.

Credits
TMDb API
Appwrite
Tailwind CSS
Vite
Note: This project is for educational/demo purposes. You must provide your own API keys for TMDb and Appwrite.
