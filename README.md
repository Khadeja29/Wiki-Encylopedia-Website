# Wiki-Encylopedia-Website
Implementation of a Wikipedia-like online encyclopedia using Django

The purpose of this project is to design a Wikipedia-like online encyclopedia using Django ,html and CSS.

### FEATURES OF THE WEBSITE: 

#### Entry Page: 
Visiting /wiki/TITLE, where TITLE is the title of an encyclopedia entry, should render a page that displays the contents of that encyclopedia entry.
The view gets the content of the encyclopedia entry by calling the appropriate util function.
If an entry is requested that does not exist, the user is presented with an error page indicating that their requested page was not found.
If the entry does exist, the user is presented with a page that displays the content of the entry. The title of the page includes the name of the entry.

#### Index Page:
Update index.html such that, instead of merely listing the names of all pages in the encyclopedia, user can click on any entry name to be taken directly to that entry page.
Search: Allows the user to type a query into the search box in the sidebar to search for an encyclopedia entry.
If the query matches the name of an encyclopedia entry, the user should be redirected to that entry’s page.
If the query does not match the name of an encyclopedia entry, the user should instead be taken to a search results page that displays a list of all encyclopedia entries that have the query as a substring. For example, if the search query were Py, then Python should appear in the search results.
Clicking on any of the entry names on the search results page should take the user to that entry’s page.

#### New Page:
Clicking “Create New Page” in the sidebar should take the user to a page where they can create a new encyclopedia entry.
Users should be able to enter a title for the page and, in a textarea, should be able to enter the Markdown content for the page.
Users should be able to click a button to save their new page.
When the page is saved, if an encyclopedia entry already exists with the provided title, the user should be presented with an error message.
Otherwise, the encyclopedia entry should be saved to disk, and the user should be taken to the new entry’s page.

#### Edit Page: 
On each entry page, the user should be able to click a link to be taken to a page where the user can edit that entry’s Markdown content in a textarea.
The textarea should be pre-populated with the existing Markdown content of the page. (i.e., the existing content should be the initial value of the textarea).
The user should be able to click a button to save the changes made to the entry.
Once the entry is saved, the user should be redirected back to that entry’s page.

#### Random Page: 
Clicking “Random Page” in the sidebar should take user to a random encyclopedia entry.

Markdown to HTML Conversion: On each entry’s page, any Markdown content in the entry file should be converted to HTML before being displayed to the user. You may use the python-markdown2 package to perform this conversion, installable via pip3 install markdown2.

### NOTE:
This project is a demonstration of the project(Project 1) for CS50 Web development with Python and JavaScript.
https://cs50.harvard.edu/web/2020/projects/1/wiki/
To view  demo follow the video link below:
https://www.youtube.com/watch?v=7ZJAFrP4VQ4&list=PLr-z4AVNOC3KInaa_alIF-EyP80eTIGv3&index=2
This is the distru=ibution code which was used to demonstarte wiki page.
https://cdn.cs50.net/web/2020/spring/projects/1/wiki.zip 
