In this exercise, you'll add code so that you can actually watch the videos on the page.
First, create a <div> to hold the video player, either below or to the side
of the list, and give it an id.

Now, in the loop where you iterate through each link, add a click listener
to the link. When you click on a link, it should display the embedded video
in the DIV you created. You should go on Youtube.com and find the embed code
for a video to figure out what that HTML should look like, and then use jQuery
to create that HTML. You can use youtube.generateEmbedUrl() from the youtube.js
library to generate the embed URL.

As a bonus, try to make the video watcher <div> fade in using jQuery.

Make sure that you use your browser developer tools to make debugging easier
while working on this. Check for errors, and use console.log() to figure out
how far your code makes it, and what the values of your variables are along the way.
