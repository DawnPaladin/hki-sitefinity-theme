# Setting up a new page on test.hki.com

1. Visit http://test.hki.com/Sitefinity/Pages?lang=en and click "Create a Page".
2. Name the page. In the "Template" section, choose "Select another Template", scroll up to find the HKI Glass template, select it, and click "Done". Click "Create and go to add content" at the bottom of the page.
3. If you want multiple columns, go into Layout mode (top-right corner), pick a columns layout from "Single and Two Columns", and drag it into the pink box that says "Drag layout elements" in the center of the page. Be sure to drag it directly into the center of the pink box; if you drop it too high or too low, your columns will span the entire width of the page, leaving no margin at the edges. When your columns are all set up, switch back to Content mode (top-right corner).
4. Drag a content block from the "Drag widgets" column on the right into the "Drag widgets here" area in the center of the page.

Now you need to add content to the content block. Click the "Edit" button and type in some content. You can use the formatting controls at the top of the editor to add bolding, links, images, and so forth.

You may need to add *CSS classes* to the widgets to get them to look the way you want. To add a class, edit the widget, click "Advanced", and scroll down until you find the "CssClass" box. Add the class you want to the box, with a space between classes, like this:

> class1 class2

The classes included in our theme are as follows:

- `no-margin-top`, `no-margin-bottom`: Widgets normally have margins, which create gaps between them. Use these widgets to remove the margins above or below the widget. (Since each widget usually has a margin above and a margin below it, if you you want to completely eliminate the gap between widgets, you'll need to apply no-margin-top to one and no-margin-bottom to the other.)
- `denest-list`: Makes the top level of a list not look like a list item. (Useful when the top level of the list is the list's title.)

Near the upper left corner there's a "Preview" button you can click to see what the page will look like without the page-building interface. When you're finished building the page, click the green "Publish" button.
