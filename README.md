# QuickNotes

QuickNotes is a simple note-taking web app built with HTML, CSS and JavaScript. You can write short notes, give each one a category, search through them and delete the ones you no longer need. Your notes are saved in the browser, so they are still there when you refresh the page.

## Features

- Add notes with a category (Personal, Work or Study)
- Notes are limited to 200 characters, with error messages for empty or long notes
- Delete individual notes, or clear all notes with a confirmation prompt
- Search notes by text (not case-sensitive)
- Note count with correct wording for zero, one and many notes
- Each category has its own colour
- Notes are saved with localStorage
- Responsive layout for phones

## How to run locally

1. Clone the repository: `git clone https://github.com/Reeescyberspacexx/quicknotes-app.git`
2. Open the folder in VS Code.
3. Install the Live Server extension if you do not have it.
4. Right-click `index.html` and choose "Open with Live Server".

## What I learned

- How to select and change elements with the DOM and build them with `createElement` and `textContent`.
- How to save and load an array of objects with `localStorage`, `JSON.stringify` and `JSON.parse`.
- How to use the render pattern: update the data, save it, then redraw the page.
- How to use Flexbox and media queries to make a layout work on phones.
- How to make small, meaningful Git commits for each part of a project.
