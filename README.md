# Notes App

This repository contains a Notes App built with React. The app allows users to create, edit, and delete notes, which are saved using the JavaScript LocalStorage feature. The app features a sidebar for recent notes and a right bar for the editor and preview option for notes, which can be written in markdown format.

![notes-app-utkarsh](https://github.com/user-attachments/assets/ec7c723b-5c52-4811-90b9-7fe0b59bb4e9)

## Live Preview

Check out the live preview of the app [https://notes-app-utkarsh.vercel.app/](https://notes-app-utkarsh.vercel.app/)

## Table of Contents
- [Getting Started](#getting-started)
- [Technologies Used](#technologies-used)
- [Approach](#approach)
- [Known Issues and Limitations](#known-issues-and-limitations)

## Getting Started

To run this application locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Utkarsh-Singhal-26/notes-app.git
    cd notes-app
    ```

2. **Install dependencies:**
    ```bash
    pnpm install
    ```

3. **Run the application:**
    ```bash
    pnpm start
    ```
    This will start the development server and you can view the app by navigating to `http://localhost:5173` in your web browser.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **LocalStorage**: A web storage API for storing data locally in the user's browser.

## Approach

The development process of this app involved the following steps:

1. **UI Construction**: Designed and built the user interface, ensuring a clean and user-friendly experience.
2. **LocalStorage Integration**: Integrated LocalStorage to save and retrieve notes.
3. **Markdown Support**: Implemented an editor and preview option for notes written in markdown format.
4. **Recent Notes Sidebar**: Added a sidebar to display a list of recent notes.

## Known Issues and Limitations

- **LocalStorage Limitations**: LocalStorage has a limited storage capacity, which might affect the app's performance with a large number of notes.
- **Error Handling**: There might be limited error handling for various edge cases, such as exceeding LocalStorage capacity or unsupported markdown syntax.

---

Feel free to reach out if you have any questions or suggestions!

Happy coding! 📝

---
