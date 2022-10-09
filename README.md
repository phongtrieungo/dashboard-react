# Dashboard implemetation

## Initialize

- The project is created using the command line: npx create-react-app with typescript as default template

- Additional packages to be installed
    - react-icons
    - react-router-dom
    - recharts => for rendering chart
    - tailwindcss => styling system
        1. Install those libs: tailwindcss postcss autoprefixer
        2. Init the tailwindcss in your project: npx tailwindcss init -p => it will create an init file named tailwind.config.js
        3. Update the regex in content field as the folder and the file extension to be browsered
        4. Adding three core modules of tailwind in index.css to be use

## Project structure

The project will use context API as its store to maintain the application state as well as the page state

- components => base components to be used across the application
- context => will contain context api function
- pages => represent for each screen
- data => contain dump data for presentation only