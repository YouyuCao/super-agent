# Notepad demo

A tiny single-file notepad: type a note, and it is saved in your browser and restored the next time you open the page.

## Open it

Open `notepad/index.html` in any modern browser. Double-click the file, or drag it into a browser window.

There is no build step and no dependencies: the HTML, CSS, and JavaScript all live in that one file.

## How it works

- Type in the text area. The note is saved to `localStorage` on every keystroke.
- **Save** stores the note immediately (handy for confirming it was saved).
- **Clear** empties the note and saves the empty note.
- On page load, the last saved note is restored.

Notes live only in the browser you used, on that device. Clearing the browser's site data removes them.
