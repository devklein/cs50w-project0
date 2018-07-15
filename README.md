# CS50w Project 0

This is my work for CS50w's project 0. The task was to build a simple website with at least 4 pages and making use of Bootstrap,
CSS, SCSS, and git.

So I created a small website with four info posting about fascia traing (in german). Just because I already had the text.

## The files:

### index.html

index.html contains a table and three bootstrap cards with an image and an excerpt of the posts. There's a butoon in every card 
which links to the blogpost page. The cards are embedded in a css grid and therefore responsive. On top iof the page is a nav bar designed
with bootstraps css.

### post_1.html, post_3.html, post_3.html

All postpages contain a single blogpost with a headline, an image and the text. They also contains the header part with the navbar.

### style.css

The stylesheet contains some particular styles which are not provided with bootstrap as well as the media query, which hides the big table on 
smaller devices.

### styles.scss

Contains all my own css styles, making use of a variable, a nested element for the list in the table and inheritance for the dates above the cards in index.html. Gets compiled to style.css with SASS.

### img folder

The image folder contains a few images which are used for the cards in index.html and as header images in every post page.