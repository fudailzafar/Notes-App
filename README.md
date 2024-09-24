# Notes App

A simple and responsive web-based notes application. This app allows users to create, edit, and delete notes, with the option to save notes locally using browser storage.

## Features

- Create new notes.
- Edit notes directly on the interface.
- Delete notes with a single click.
- Automatically saves notes using local storage, so notes persist even after refreshing the page.
- Responsive design, compatible with different screen sizes.

## File Structure

```bash
├── index.html               # Main HTML file
├── styles.css               # CSS file for styling
├── script.js                # JavaScript logic for handling notes
├── images/                  # Folder containing icons
    ├── notes.png            # Icon for the notes header
    ├── delete.png           # Icon for the delete button on each note
    └── edit.png             # Icon for the create notes button
```

## How to Use

1. Open the **index.html** file in your browser.
2. Click on the **Create Notes** button to add a new note.
3. Edit the content of the note by typing directly into the input box.
4. To delete a note, click on the delete icon in the bottom right of the note.
5. The app automatically saves your notes using local storage, so they will still be there when you close and reopen the browser.
