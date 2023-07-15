Help LLC Landscaping Website - Owner's Editing Guide (GitHub)
=============================================================

This guide provides instructions for the owner of Help LLC, a landscaping website, on how to edit HTML text and change photos using GitHub. By following these steps, you can easily update content and replace images without cloning the repository.

Table of Contents
-----------------
* [Prerequisites](#prerequisites)
  * [Locate the HTML File](#locate-the-html-file)
  * [Add or Replace Photos](#add-or-replace-photos)
    + [Adding New Photos:](#adding-new-photos-)
    + [Replacing Existing Photos:](#replacing-existing-photos-)
  * [Update Image References](#update-image-references)
  * [Edit HTML Text](#edit-html-text)
    + [Updating Phone Numbers and Addresses](#updating-phone-numbers-and-addresses)
    + [Using Shortcuts for Bulk Edits](#using-shortcuts-for-bulk-edits)
  * [Commit and Deploy](#commit-and-deploy)
  * [Conclusion](#conclusion)

Prerequisites
-------------

To follow the steps in this guide, you will need:

-   Access to the Help LLC landscaping website repository on GitHub.
-   Basic understanding of HTML markup.
-   Text editor or Integrated Development Environment (IDE) to edit HTML files.
-   Images you want to add or replace.

Locate the HTML File
--------------------

1.  Open the Help LLC landscaping website repository on GitHub.
2.  Navigate to the HTML file you wish to edit. For example, if your homepage is named `index.html`, open that file.

Add or Replace Photos
---------------------

### Adding New Photos:

1.  Create an `images` folder in the repository if it doesn't already exist. This is where you will store your images.
2.  Upload the image you want to add to the `images` folder.

### Replacing Existing Photos:

1.  Locate the image you want to replace in the `images` folder.
2.  Upload the new image file, ensuring that the new image has the same file format (e.g., JPEG, PNG) and a similar size. Overwrite the existing image file.

Update Image References
-----------------------

1.  Open the HTML file in a text editor or IDE.
2.  Search for the `<img>` tags or any other HTML elements that reference the images you added or replaced.
3.  Modify the `src` attribute of the `<img>` tag to reflect the new image file's name.
    -   Example: `<img src="images/old-photo.jpg" alt="Old Photo">` becomes `<img src="images/new-photo.jpg" alt="New Photo">`
4.  Repeat this process for all the image references you want to change.

Edit HTML Text
--------------

1.  Open the HTML file in a text editor or IDE.
2.  Locate the section of the HTML file that contains the text you want to edit.
3.  Update the text content as desired. Be cautious not to modify any HTML tags or attributes unless you have the necessary knowledge.
4.  Save the changes.

### Updating Phone Numbers and Addresses

To update phone numbers and addresses on multiple pages, follow these steps:

1.  Use the search functionality in your text editor or IDE to find all occurrences of the old phone number or address.
2.  Replace the old information with the new phone number or address.
3.  Save the changes.

### Using Shortcuts for Bulk Edits

To perform bulk edits, such as updating dates or other repetitive content, you can take advantage of text editor shortcuts or find-and-replace functionality:

1.  Use the appropriate shortcut in your text editor or IDE to find and select the content you want to update. For example, you can use Ctrl+F (Windows) or Command+F (Mac) to open the find functionality.
2.  Enter the search term or pattern you want to find, such as a specific date format or phrase.
3.  Use the replace functionality to update the content with the desired changes.
4.  Review and verify the changes before saving.

Commit and Deploy
-----------------

1.  Go back to the Help LLC landscaping website repository on GitHub.
2.  Navigate to the modified HTML file.
3.  Click the "Edit" button to make changes directly on the GitHub interface.
4.  Make sure you have described your changes in the provided field.
5.  Commit the changes.
6.  GitHub will automatically update the website, and you can verify the changes by visiting the website's URL.

Conclusion
----------

By following these steps, you, as the owner of Help LLC, can easily edit HTML text and change photos on your landscaping website using GitHub. Remember to update the image references and commit the changes to see them deployed on the live website. Utilize shortcuts and find-and-replace functionality in your text editor to streamline bulk edits. Regularly update your website's content to provide accurate and up-to-date information to your visitors.
