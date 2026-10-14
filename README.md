# BookTrack

BookTrack is a simple, responsive web app for keeping track of books I want to read, am currently reading, or have finished. I built it with HTML, CSS, and JavaScript.

## Project links

- **Live website:** Add your GitHub Pages URL after publishing.
- **GitHub repository:** Add your public repository URL after creating it.

## What the app can do

- Add a book with its title, author, and reading status.
- Require a title and author, with a message beside a missing field.
- Show recently added books at the top of the list.
- Search books by title or author, without case-sensitive matching.
- Filter the list by reading status.
- Change a book's status or delete it from the shelf.
- Save the list in the browser so it remains after refreshing the page.
- Adjust the layout for desktop, narrow windows, and phone-sized screens.

## How to use it

1. Enter a title and author.
2. Choose a reading status and select **Add to My Shelf**.
3. Search or use the status filters to find books.
4. Use the status menu on a book to update it, or select **Delete** to remove it.

## Run the project

Open `index.html` in a modern web browser. The project uses plain HTML, CSS, and JavaScript, so it does not need a package installation or build step.

## Saving and privacy

BookTrack saves books in the browser's `localStorage`. The saved list belongs to that browser and site address; it is not automatically shared between different browsers, devices, or addresses such as `file://` and `localhost`. A private browsing window may also have separate storage.

## Built with

- HTML
- CSS
- JavaScript
- Browser `localStorage`

## Project files

- `index.html` — app layout, styles, and functionality.
- `PROMPTS.md` — example prompts used while developing and improving the project.
