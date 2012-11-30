In this exercise, you'll use jQuery's $.ajax function to pull in a JSON file
and turn it into DOM, using the same functions as we did for the in-page JSON.

Use Firefox for this assignment, as Chrome has a permissions policy for local file:// testing
that disallows AJAX requests.

Go through these steps, and do as many as you can in the time we have:

1) Start with step4_solution.html. 

2) The webpage currently has an in-page JSON describing the videos, and we want to put that into a separate file. Make a file in your project folder called videos.json, and copy the value of the videos variable into that file. Delete the variable from the page.

3) Use the jQuery $.ajax function to bring in the data from videos.json. In the success callback,
iterate through the videos and render each one into the page, using the addVideoToList function that we already have.
Look at the slides and the jQuery documentation to remember how to use the $.ajax function.

Bonus: Create another JSON file with another set of videos, and bring that into the page as well.
Try to generalize your code so that you could bring any number of JSON files in.


--------------------

Make sure that you use your browser developer tools to make debugging easier
while working on this. Check for errors, and use console.log() to figure out
how far your code makes it, and what the values of your variables are along the way.

