Welcome!

This project is about displaying a game browser.

Included in this project are two files:

	- games.json
	- start.html
	
The first, `games.json`, is to basically be left alone. It represents the data source you'll be working from. It contains an array of information for some games.

The second, `start.html`, is to be modified, tweaked, replaced, enhanced - whatever you like!

It simply loads the JSON file by Ajax, and renders the first 15 game images into the HTML.

It uses bootstrap and jQuery, but those are completely optional and can be replaced.

From this point on, it's up to you! Basically... make it better!

Some ideas you could choose to implement:

- Improve the basic display of the game items, including hover status
- Display the game name and/or description
- Display a "NEW" sticker on any games published in the last X months
- Paginate the games to show page by page (allow the user to change the page, prev/next)
- Implement an "infinite scroll" where it loads the games as required
- Order the games by... date published, alphabetically, rtp, or whatever criteria you like
- Add a "search" feature so the user can search for a game by name
- Display the games in... circles, hexagons, 3d cubes

Note that you do NOT need to style the rest of the page, just the games list widget.

Make everything as responsive as possible, using a mobile-first approach.

Feel free to use our brand colours from the 32red.com website, but don't feel you have to.

Only one size image is given for the games, but others are available. For each game, the game icon is available in 4 sizes:

(Example for one game)

https://static.32red.com/games/game-icon/default/191-thunderstruck_2.jpg
https://static.32red.com/games/game-icon-big/default/191-thunderstruck_2.jpg
https://static.32red.com/games/game-icon-tall/default/191-thunderstruck_2.jpg
https://static.32red.com/games/game-icon-wide/default/191-thunderstruck_2.jpg

You can use these however you like.

Don't feel you need to try and copy the game grid layout of 32red.com - make something else!

Less is more; this isn't a month-long challenge; it's far better to implement one or two ideas well than attempt to implement 10 badly or incompletely.

Too easy? Want more of a challenge?
===================================

You can implement some backend functionality if you like - PHP is preferred here.

- Have the clicks ("plays") on the games recorded and remembered, so you can display the user's recently played games
- Do the filtering and sorting on the server side

Deliverables
============

Either a packaged .zip file, or push to an online repo (bitbucket, github, ...) and deliver the repo URL.