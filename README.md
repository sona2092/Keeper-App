# Keeper App

A simple **ReactJS** application inspired by Google Keep that allows users to add, view, and delete notes. This project is built to practice React components, state management, and basic event handling.

## Features

- Add notes with a title and content.
- Delete notes individually.
- Clean and minimal UI using CSS.

## Project Structure

```
ReactJS-keeper-app/
|
|-- public/
|   |-- index.html       # Main HTML file
|
|-- src/
|   |-- App.js           # Main application component
|   |-- Header.js        # Header component
|   |-- Footer.js        # Footer component
|   |-- Note.js          # Individual note component
|   |-- CreateArea.js    # Form for adding notes
|   |-- index.js         # Entry point for the app
|   |-- styles.css       # Main CSS styles
|   |-- styles1.css      # Additional styles
|
|-- package.json         # Project dependencies and scripts
|-- .eslintrc.json       # ESLint configuration
```

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/keeper-app.git
   cd keeper-app
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Run the App**

   ```bash
   npm start
   ```

   The app will open in your browser at `http://localhost:3000`.

## Dependencies

- **React**: JavaScript library for building user interfaces.
- **ReactDOM**: DOM bindings for React.

These dependencies are defined in the `package.json` file.

## Components

### 1. Header
Displays the title of the Keeper App.

### 2. Footer
Displays the footer with the current year.

### 3. Note
Renders individual notes with a title and content, and a delete button.

### 4. CreateArea
Form for adding new notes with input fields for title and content.

### 5. App
Combines all components and manages the state for adding and deleting notes.

## Screenshots
Add screenshots here (if applicable).

## How to Contribute

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Commit your changes: `git commit -m "Add a new feature"`.
4. Push the branch: `git push origin feature-branch-name`.
5. Open a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
