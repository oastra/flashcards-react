# Flashcards

This project is a simple React application that simulates a flashcard system. Each flashcard presents a question, and when clicked, it reveals the answer. This project helps users learn and revise concepts interactively.

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

#### `npm run eject`

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Project Structure

- `index.js`: The entry point for the React application, where the root component is rendered.
- `App.js`: The main component that manages the flashcards and handles the logic for displaying questions and answers.
- `index.css`: Contains all the styles used in the application, ensuring a clean and responsive design.

## Project Overview

The application consists of a set of flashcards, each containing a question related to React. When a user clicks on a flashcard, the question is replaced with the corresponding answer. Clicking again toggles the display back to the question.

### Components

- **App.js**: The main application logic, including rendering the flashcards and handling the click events.
- **FlashCards.js**: A component that maps through the questions and displays each as a flashcard.
- **index.css**: Provides the necessary styles for the flashcards, including layout, colors, and hover effects.

### Styling

- **index.css**: Defines the styling for the application, including the grid layout for the flashcards and the visual states for selected and unselected cards.

### Dependencies

- `react`: The core library for building the user interface.
- `react-dom`: Handles the rendering of React components.

### Author

- **Olha Chernysh**
