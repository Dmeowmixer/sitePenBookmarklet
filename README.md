# Assumptions:

* Website to analyze - https://themeisle.com/blog/best-free-blogging-sites/
* Words are separated by Spaces (currently targeting <p> tags), however, additional tags can be targeted and added to the wordArray before processing.
* Browser - Chrome 71, JS Enabled

# Notes:
* Running localhost server on port:8000 w/ Python -m 'SimpleHTTPServer'
* Bookmarklet renders on localhost as <a> and dragged into bookmarks bar
* <div id="sitePenResultsDiv"> created on running bookmarklet code, will append to bottom of page
* Sizes are set utilizing creation of h1 to h4 tags (I tried setting a fontSize property which I could not get to work despite trying to clear styles. Would try to reimplement variable appeared * 10 fontSize given more time for better representation of # of word appearances)
* Did not minify code for readability purposes