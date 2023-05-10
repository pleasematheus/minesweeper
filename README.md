# Minesweeper
This documentation provides an overview and explanation of the code for the React Native app.

## Introduction
This app is a Minesweeper game built using React Native. It allows users to play the classic Minesweeper game on their mobile devices. The game board consists of a grid of cells, some of which contain hidden mines. The objective of the game is to uncover all the cells that do not contain mines without triggering an explosion.

## Installation
To install and run the app, follow these steps:

Make sure you have Node.js and npm installed on your machine.
Clone the project repository.
Navigate to the project directory in your terminal.
Run `npm install` to install the project dependencies.
Run `npm start` to start the Metro bundler.
Connect a mobile device or launch an emulator to run the app.
Run npm run android or npm run ios to build and run the app on Android or iOS, respectively.

## Code Structure
The code for the app is organized into different files and components:

`src/components/Header.js`: This component displays the game header, including the number of flags left and buttons for starting a new game and selecting the game level.
`src/components/MineField.js`: This component renders the game board grid, consisting of multiple MineCell components.
`src/screens/LevelSelection.js`: This component provides a modal for selecting the game difficulty level.
`src/functions.js`: This file contains various helper functions for manipulating the game board, such as creating a mined board, cloning the board, opening a field, checking for explosions, checking for a win, showing mines, inverting flags, and counting used flags.
`src/params.js`: This file defines the game parameters, such as the number of rows and columns and the difficulty level.
The main app component is defined in the App.js file. Let's go through the code and explain its functionality.
