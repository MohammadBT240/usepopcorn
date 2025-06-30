# 🍿 usePopcorn

A modern React app for searching, rating, and tracking movies you've watched. Built with Create React App and powered by the OMDb API.

## Features

- **Movie Search:** Search for movies by title using the OMDb API.
- **Movie Details:** View detailed information about each movie, including plot, cast, director, and more.
- **Star Rating:** Rate movies with a customizable star rating component.
- **Watched List:** Add movies to your watched list, rate them, and track your viewing stats.
- **Persistent Storage:** Your watched list is saved in your browser's localStorage.
- **Responsive UI:** Clean, modern, and responsive design.

## Demo

![usePopcorn Screenshot](public/logo192.png)

## Getting Started

### Prerequisites

- Node.js (v14 or higher recommended)
- npm (v6 or higher)

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repo-url>
   cd usepopcorn
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm start
   ```
   The app will open at [http://localhost:3000](http://localhost:3000).

### Build for Production

```bash
npm run build
```

This will create an optimized production build in the `build` folder.

## Project Structure

```
usepopcorn/
  public/
    index.html
    favicon.ico
    ...
  src/
    App.js
    App.css
    starRating.js
    index.js
    ...
  package.json
  README.md
```

## Customization

- **OMDb API Key:** The app uses a demo API key. For production, get your own key from [OMDb API](http://www.omdbapi.com/apikey.aspx) and update the `KEY` constant in `src/App.js`.
- **Star Rating:** The `starRating.js` component is reusable and customizable (color, size, max stars, etc).

## Scripts

- `npm start` – Run the app in development mode.
- `npm test` – Run tests.
- `npm run build` – Build for production.
- `npm run eject` – Eject configuration (not recommended).

## Learn More

- [React documentation](https://reactjs.org/)
- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)
- [OMDb API](http://www.omdbapi.com/)

## License

This project is open source and available under the [MIT License](LICENSE).
