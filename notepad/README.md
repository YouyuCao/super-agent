# Notepad demo

A tiny single-file notepad: type a note, press **Save**, and it is added to a list of saved notes below the text area. Each saved note shows the time it was saved and has **Edit** and **Delete** buttons. Everything is kept in your browser.

## Open it

Open `notepad/index.html` in any modern browser. Double-click the file, or drag it into a browser window.

There is no build step and no dependencies: the HTML, CSS, and JavaScript all live in that one file.

## How it works

- Type in the text area. Your draft is saved to `localStorage` on every keystroke and restored when you reopen the page.
- **Save** adds the note to the **Saved notes** list with the current time and clears the text area.
- **Edit** loads a saved note back into the text area; the button becomes **Update**. **Cancel** restores the draft you had before editing.
- **Delete** removes a saved note from the list.
- **Clear** empties the current draft (saved notes are not affected).

Notes and the draft live only in the browser you used, on that device. Clearing the browser's site data removes them.
