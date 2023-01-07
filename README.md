## Description

The markdown-notes-app is an easy-to-use ui for taking notes. It uses the react-mde package for the Editor component and functionality has been added to store the notes on the local storage of the browser. Also, the tabs in the sidebar get updated automatically to list the the most recently updated notes on the top. You can also easily delete notes using the UI and give each note a particular title.

# Preview:

// add image here.

- The `public` directory contains the html page
- The `src` directory contains the images and the components folder and all other js and css files.
- The project has 2 components:
  - `Editor.js`: includes the 'write' and 'preview' tabs of the editor sections which is based on the react-mde package
  - `Sidebar.js`: The sidedbar includes the functionality to add new notes, delete old notes and switch between different notes
- `App.js` then uses `Editor.js` and `Sidebar.js`and exports the bundled component to `index.js`
- `index.js` renders the page using `style.css`

## Installation

The dependencies required are all included in the `package.json` file. They will all be installed by running the `npm install` command.

## Set-up

To start the project run `npm start`.

## Technologies

This project was bootstrapped with create-react-app. `npx create-react-app`.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
  <source media="(prefers-color-scheme: light)" srcset="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
  <img width="30px" alt="Shows a logo of c-sharp" src="https://cdn.icon-icons.com/icons2/2415/PNG/512/react_original_wordmark_logo_icon_146375.png">
</picture>
