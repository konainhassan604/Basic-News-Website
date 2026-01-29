# NewsWave - Basic News Website

A simple and responsive news application built with React and Vite that fetches real-time news articles using the NewsAPI.

## Features

- **Live News Feed:** Fetches the latest headlines from the US.
- **Categories:** Filter news by Business, Entertainment, Health, Science, Sports, and Technology.
- **Responsive Design:** Styled with Bootstrap 5 for a clean and mobile-friendly interface.
- **Real-time Updates:** Automatically refreshes the news feed when switching categories.

## Technologies Used

- **React:** Frontend library for building the user interface.
- **Vite:** Fast build tool and development server.
- **Bootstrap 5:** CSS framework for styling and responsiveness.
- **NewsAPI:** External API for fetching news data.

## Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

- Node.js installed on your machine.
- An API key from [NewsAPI](https://newsapi.org/).

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd Basic-News-Website
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add your NewsAPI key:
   ```env
   VITE_API_KEY=your_api_key_here
   ```

4. **Run the development server:**
   ```bash
   npm run dev
   ```

5. **Open in Browser:**
   Visit `http://localhost:5173` (or the URL shown in your terminal).   
   

## Project Structure

- `src/components/NavBar.jsx`: Navigation bar with category links.
- `src/components/NewsBoard.jsx`: Main component that fetches and displays the list of news articles.
- `src/components/NewsItem.jsx`: Component for rendering individual news cards.
- `src/App.jsx`: Root component that manages the category state.

## License

This project is open-source and available for educational purposes.
