# Responsive Resume

##Introduction
This is a simple template to help you create a mobile first responsive resume.
Feel free to download and use to suit your needs. No attribution is required, though I would love to see what you make!
If you have any questions feel free to contact me via twitter <a href="http://www.twitter.com/philipcdavis">@philipcdavis<a>.
If you notice anything that is broken or that could be improved you can <a href="https://github.com/philipcdavis/responsive-resume/issues">open an issue</a>.



##Setup Instructions
####Step 1: Download and Extract
<a href="https://github.com/philipcdavis/responsive-resume/archive/master.zip">Download</a> and extract the template and put it in whatever folder you want.

####Step 2: Import a headshot
Once you have a picture you want to use import it into the `/img` folder and override the `background.jpg` file.
Copy either format.html/formal.css or modern.html/modern.css to index.html/style.css.
This image is set as the background image of the `header` in style.css, use a high quality photo with padding on all sides for best results.

####Step 3: Edit the index.html file
Using your favorite text editor open your index.html file to fill out content, update your name, skills, and information.
Feel free to remove or rearrange the content blocks to fit your needs.

####Step 4: Host your site
<a href="https://pages.github.com/">Github pages</a> allows your to host for free and there is plenty of documentation on how to get set up.



##Grid
The 6 column mobile first grid is used by wrapping each row with the `.row` class.
Each row should have grid units that add up to 6 (with the exception of the Gallery).
You can view the grid with its classes on the <a href="http://philipcdavis.com/responsive-resume/">homepage</a>.

##Custom Blocks
This template comes with multiple components that can be removed or rearranged to suit your particular needs.
These are built on top of the grid, but container some useful layouts that you can use depending on your situation.
Each block is contained by the `<section>` tags. With some blocks it is helpful to include a separating `<hr>` tag.
Below you will find information for each block. If you notice anything that should be improved please <a href="https://github.com/philipcdavis/responsive-resume/issues">open an issue</a>.

####Gallery
The Gallery is useful for displaying a grid of images. It is similar to the normal grid with two exceptions.

1. Each grid item has a top and bottom margin.
2. The `.grid-2` and `.grid-3` classes have a default two column layout instead of normal one column layout.

For the gallery you can wrap everything inside a `.row` class.

####Testimonials
This section is great for highlighting some things other people have said about you.
These images have a fixed height in order to keep everything aligned.

####Spotlight
The Spotlight section is useful for highlighting one project or accomplishment.
In order to keep the theming consistent with the project you are able to edit the `.spotlight` classes in style.css.
The image you use for an icon can be transparent; it will be centered and restricted within the `.grid-3` class.
It's important that this block is outside of the container so that the bar can extend the full width of the screen.

####Education
This section is fairly self-explanatory.
You want to watch out for word-wrap issues that cause text to look awkward, if you need more room you can change the `<h2>` tag to a `<h3>`.

####Experience
This is a great section to bring some of the more formal resume elements onto the web.
All the jobs are separated by a bottom-border with the exception of the last one.

##Formal Theme
The formal theme is useful if you are looking for a more traditional layout.
The formal.html, and formal.css files are all you need to get started.
If you are not using this theme feel free to remove it from your folder.
