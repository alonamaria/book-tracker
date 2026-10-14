## Five most important prompts

1. **Add books and validate required fields**
"Review my plain HTML, CSS, and JavaScript book tracker. Make sure I can add a book with a required title, author, and reading status. Show a clear message beside a missing title or author, and do not add the book when either is blank."

2. **Keep the newest books at the top**
 "Show the most recently added books first, including when search or status filters are active. Use each book's creation timestamp without mutating the saved array just to sort the display."

3. **Save books and support search**
"Save each book's title, author, status, and creation time in localStorage. Load the list on page open so books and their statuses remain after refreshing. Add a case-insensitive search for title or author."

4.. **Make the interface work on phones**
"Make the existing book tracker comfortable to use at phone widths and in a narrow desktop window. Keep all controls readable and usable without horizontal scrolling, and make sure Delete is visible on touchscreens."

5. **Improve visual clarity without changing behavior**
"Improve the visual hierarchy and contrast of the headings, status controls, and Delete action while preserving the book-themed style, responsive layout, and existing behavior."

## Manual test results

Tested the live site in a browser:

- Tried adding a book once with a blank title and once with a blank author. Each attempt showed the corresponding validation message and did not add a book.
- Added a temporary test book and refreshed the page. The book remained on the shelf.
- Changed a book's status, refreshed, and confirmed the new status remained saved.
- Searched for "BEN" and confirmed that "Benyamin" was found.
- Filtered by Finished and confirmed only finished books appeared.
- Deleted the temporary test book and confirmed it was removed. The shelf was restored to its original six books.


## One time the AI got it wrong

The AI initially said the page was ready for phones, but the Delete button was hidden until hover, which is not reliable on a touchscreen. I pointed out the issue and asked for the mobile controls to stay visible, and the layout was updated so Delete is easy to find and tap.

## Anything unfinished

Nothing is currently noted as unfinished. The app includes adding, searching, filtering, changing status, deleting books, and saving the list in the browser.

