In this exercise, you'll try out using several HTML APIs to add more dynamic content to the starter webpage.

Go through these steps, and do as many as you can in the time we have:

1) Start with step6_starter.html. Open the webpage up in the browser and make sure it works. It should pull in video information via an AJAX request and display linked video thumbnails in a list.

AJAX requests do not work from URLs that start with file:// in Chrome, so if you get an error that "XMLHttpRequest cannot load ", you need to either do your development in Firefox, or run a simple server on your machine using this command from your project foldr:
python -m SimpleHTTPServer

You should then be able to access your project folder at http://localhost:8000

2) Go to http://www.flagcounter.com/ and set up a hit counter for your website. Put the counter somewhere near the bottom of the page.

3) Go to https://developers.google.com/chart/image/docs/gallery/googleometer_chart and read about the Google-o-meter image chart API. Generate a chart for each video that shows its rating (from the JSON). Display that chart when you click on the video. Try generating the chart URLs in the browser first, and only code it in JavaScript once you know what you want the URLs to look like.

Bonus: Create a bar chart that compares the ratings across all the videos, using the Google Bar Charts Image API: https://developers.google.com/chart/image/docs/gallery/bar_charts

--------------------

Make sure that you use your browser developer tools to make debugging easier
while working on this. Check for errors, and use console.log() to figure out
how far your code makes it, and what the values of your variables are along the way.

