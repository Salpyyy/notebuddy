# Meeting Notes

A simple notes app inspired by early iPhone Notes.

- Five themes: Legal pad, White, Blank, Futuristic, Frutiger Aero
- Several notes, with search
- Rich text from the right-click menu: bold, italic, underline, strikethrough, headings, bulleted, numbered and checklists
- Tab indents text like Word; inside a list it moves the item in or out
- Shortcuts: Ctrl+Shift+X strikethrough, Ctrl+Shift+H heading, Ctrl+Shift+7/8/9 lists, Ctrl+Enter tick a checklist item
- Images: paste, drag and drop, or right-click → Insert image
- "Make project files" exports a note as a .zip of Markdown files

On the Netlify version, notes are kept in your browser (localStorage) only. AI organizing of notes only works when the app is opened inside Claude.

Static site with no build step: `index.html` is the whole app.
