# Problem Sheet - Curl

Exercises from curl problem sheets - Data Representation & Querying

The following exercises are related to the use of the command line tool curl [1].
* 1. Create a git repository for your answers to this problem sheet. Push the repository to
GitHub. Make a commit and push it to GitHub after each exercise.
* 2. Use curl to download the HTML page located at http://www.jmarshall.com/easy/
http/, and save its contents to a file named http-easy.html. Open the URL in a browser,
and compare the source of the page to the file you created using curl.
* 3. Use curl to download the contents of the HTML page located at http://www.duckduckgo.
com, saving the contents to a file named duckduckgo.html. Open the URL in a browser,
and compare the source of the page to the file you created using curl. Investigate the
HTTP transaction using curl’s verbose mode. Try to redirect the output from curl to a
file called duckduckgo.txt.
* 4. In your browser, search for the term GMIT using DuckDuckGo. Note the URL in the
browser’s location bar. Adapt the URL and use it, with curl, to save the response
from DuckDuckGo when searching for science to science.txt. Do the same for the term
computer science, saving the response to computer-science.txt.
* 5. Use curl to save the response from http://duckduckgo.com/?q=gmit&format=json to
the file gmit.json. Open the file and re-format it by adding white space to make it easier
to read.
* 6. Create a folder called www. Save the blank template from the Basic Template section of
http://getbootstrap.com/getting-started/, saving it as index.html in www. Run
a Python SimpleHTTPServer in www, and access the webpage in your browser. Open
another terminal windows and use curl to access it. Fix the broken JavaScript and CSS
links in the file, pointing to a CDN. Dow
