# NovelAI Taghelper

This is a simple in-browser utility designed for support AI art prompt building/organization in [NovelAI](https://novelai.net/image).

## Usage
Add tags using either the textfield or the `+` button. Tags can be edited by double-clicking and moved around with drag and drop. Once you have finished organizing your taglist, the full prompt can then be copied to the clipboard through the `<>` button.

## Controls and Features

 - `+` (at the top menu): Appends a new tag to the bottom of the list. This tag can then be renamed by double-clicking the tag item.
 - Mouse drag-and-drop: Reorders the selected tag to the mouse position. Users may also delete tags by spilling (dragging tags outside the taglist area).
 - `x`: Clears all tags from the taglist.
 - `↓`: Saves current tags to local storage (persists taglist on page reload).
 - `<>`: Copies current taglist (ordered) to the clipboard. The output separates each tag is separated by `,` (comma) and replaces `_` (underscore) danbooru-style tag notation to ` ` (whitespace) characters.
 - `+` (at taglist): Raises tag priority -- encloses the tag with `{}` each time it is clicked. If the tag is enclosed by `[]`, it removes one pair of the square brackets instead.
 - `—`: Lowers tag priority -- encloses the tag with `[]` each time it is clicked. If the tag is enclosed by `{}`, it remove one pair of the curly brackets instead.
