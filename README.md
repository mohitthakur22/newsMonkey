# NewsMonkey

A modern, responsive news application built with React that fetches and displays the latest news articles from various categories.

## Features

- **Infinite Scrolling**: Seamlessly load more articles as you scroll.
- **Category-based News**: Browse news by categories like general, business, entertainment, health, science, sports, and technology.
- **Loading Indicators**: Visual feedback with a top loading bar and spinner.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **React Router**: Navigate between different news categories without page reloads.

## Technologies Used

- **React**: Frontend library for building user interfaces.
- **React Router DOM**: For client-side routing.
- **React Infinite Scroll Component**: For implementing infinite scrolling.
- **React Top Loading Bar**: For displaying loading progress.
- **Create React App**: For project setup and build tools.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/mohitthakur22/newsMonkey.git
   ```

2. Navigate to the project directory:
   ```
   cd newsMonkey
   ```

3. Install dependencies:
   ```
   npm install
   ```

## Usage

1. Start the development server:
   ```
   npm start
   ```

2. Open your browser and go to `http://localhost:3000` to view the application.

## Available Scripts

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner in interactive watch mode.
- `npm run build`: Builds the app for production to the `build` folder.
- `npm run eject`: **Note: This is a one-way operation!** Ejects from Create React App.

## Project Structure

```
src/
├── components/
│   ├── Navbar.js          # Navigation bar component
│   ├── News.js            # Main news component with infinite scroll
│   ├── NewsItem.js        # Individual news article component
│   └── Spinner.js         # Loading spinner component
├── App.js                 # Main application component
├── index.js               # Application entry point
└── ...
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is private and not licensed for public use.