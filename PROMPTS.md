1. **Add books and validate required fields**

   > Review my existing plain HTML, CSS, and JavaScript book tracker before changing it. Make sure I can add a book with a title, author, and reading status. Title and author must be required; if either is blank, show a clear message beside that field and do not add the book. Preserve the current design and test both missing-field cases.

2. **Keep the newest books at the top**

   > Update the book list so the most recently added books always appear first, including when search or status filters are active. Use each book's existing creation timestamp, do not mutate the saved array just to display the sorted results, and verify the order with books added at different times.

3. **Save books and support search**

   > Save the complete book list—including each book's title, author, status, and creation time—in localStorage. Load it when the page opens so refreshing keeps the books and their statuses. Add or verify a search that matches title or author without case sensitivity (for example, searching "BEN" finds "Benyamin"). Test adding, searching, changing status, and refreshing.

4. **Make the interface work on phones**

   > Make the existing book tracker comfortable to use at phone widths and in a narrow desktop window. Keep the form fields, search, filters, book details, status selector, and delete action readable and usable without horizontal page scrolling. Ensure touch controls are easy to tap and the delete action is not hidden behind hover. Check at 375px and 320px wide.

5. **Improve visual clarity without changing behavior**

   > Improve the visual hierarchy of all the heading and each book's status and delete controls. Make the controls high-contrast, clearly labeled, and easy to find on both desktop and touchscreens, while preserving the existing warm book-themed style, responsive layout, and all current behavior. Verify the result at desktop and phone widths.

## One time the AI got something wrong

The AI initially said the page was ready for phones, but the Delete button was hidden until hover, which does not work reliably on touchscreens. I asked for the mobile controls to stay visible, and it updated the layout so the Delete button is easy to find and tap.
