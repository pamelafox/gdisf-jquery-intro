In this exercise, you'll be turning this linked list of titles into a linked list of thumbnails,
using JavaScript DOM manipulation and the functions from the youtube.JS library.

Step by step:

Create an array of every link on the page using document.getElementsByTagName(tagName)
Iterate through the array. In each iteration of the loop: 
    Find the current href using element.getAttribute(name), and store into a variable
    Generate a thumbnail URL using youtube.generateThumbnailUrl(videoUrl)
    Create an IMG element using document.createElement(tagName) 
    Set the "src" of the IMG element using element.setAttribute(name, value)
    Append the IMG to the link using element.appendChild(element)
