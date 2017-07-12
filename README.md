# Books and Bookcases

This module adds the ability to read and write books, as well as store them in bookcases.

To get a book, simply type `give book_name` in the console. For e.g. - `give redBook`.

To obtain the quill, simply type `give quill` in the console. 

To obtain a bookcase, simply type `give bookcase 1` in the console.

To read a book, simply right click on with the book selected from the inventory.

To edit a book, click on the edit button that appears under each page while reading.

**Note:** Not all books are editable. Some books are read only. To edit a book make sure that it is not read only. Check for the Book component in prefab to be defined as `"readOnly" : false`. In addition, to edit a book the player must possess the Quill item (`give quill` in console).

### Books available-
- Bluebook (editable)
- Book (editable)
- RecipeBook (editable)
- RedBook (read-only)

Credits for images:
- Quill - https://openclipart.org/detail/262818/vintage-feather-inkwell