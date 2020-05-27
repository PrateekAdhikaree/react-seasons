# Seasons

![display](public/display.jpg 'display')

## Tools Used

- react-js [[Ref]](https://reactjs.org/docs/getting-started.html)

## Running the project

In the project directory, you can run:

### `npm i`

Installs the required packages in node_modules directory

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

## React Components

**main file**: [index.js](src/index.js)

- [App](src/index.js)
  - [useLocation](src/useLocation.js)
  - [SeasonDisplay](src/SeasonDisplay.js)
  - [Spinner](src/Spinner.js)

## Flow

1. User allow (or does not allows) location request in the browser

![spinner](public/spinner.jpg 'spinner')

2. If location granted, show the styling based on the simple below logic

Season is calculated based on:

- Geo-location data (latitude)
- Current month

![season-logic](public/season-logic.jpg 'season-logic')

#### Credits

Stephen Grider [Modern React with Redux [2020 Update]](https://www.udemy.com/course/react-redux/)
