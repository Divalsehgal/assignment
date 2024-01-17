# Mention Box App

This is a simple React application created with Vite, implementing a mention box similar to the ones used in Twitter or Slack. Users can type in the input box, start with "@" to mention someone, and the application will filter names from the provided data.

## Features

- Input box with mention functionality.
- OptionsBox component to display filtered names.
- Utilizes React, Vite, and testing library for development.

## Project Structure

```plaintext
src/
|-- components/
|   |-- Input/
|   |   |-- Input.tsx
|   |-- OptionsBox/
|   |   |-- OptionsBox.tsx
|   |-- MentionBox/
|   |   |-- MentionBox.tsx
|-- data.json
|-- App.tsx
|-- main.tsx
|-- index.html
