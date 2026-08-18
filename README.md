# Textifyy

A fast text transformation tool built with React. Type or paste your text and convert it to UPPERCASE, lowercase, or Title Case, copy it to the clipboard, or clear it — with live character and word counts and multiple color themes including dark mode.

## Live Demo

https://musawarahmed.github.io/Text-transform

## Features

- Convert text to **UPPERCASE**, **lowercase**, or **Title Case**
- Copy text to clipboard in one click
- Clear text instantly
- Live **character count** and **word count**
- Color themes: light, purple, orange, blue, and dark mode
- Fully responsive layout

## Tech Stack

- [React 18](https://react.dev/)
- [Vite 5](https://vitejs.dev/)
- [React Router 6](https://reactrouter.com/)
- [Bootstrap 5](https://getbootstrap.com/) (via CDN)
- GitHub Actions for CI and GitHub Pages deployment

## Getting Started

```bash
# install dependencies
npm install

# start the dev server (opens http://localhost:3000)
npm run dev

# build for production (output in build/)
npm run build

# preview the production build
npm run preview
```

## Project Structure

```
src/
├── index.jsx            # React entry point
├── App.jsx              # Routes, theme state, alert handling
└── Components/
    ├── Navbar.jsx       # Navbar + theme color picker
    ├── Navbar.css       # Navbar & theme styles
    ├── TextForm.jsx     # Text transformation form
    ├── TextFrom.css     # Form & button styles
    ├── Alert.jsx        # Bootstrap alert banner
    └── About.jsx        # About page
```

## License

ISC
