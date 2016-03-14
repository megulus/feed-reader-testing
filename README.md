## Project Overview

The starting point of this project was a web-based application that reads RSS feeds and the skeleton of a Jasmine testing suite. 

## Feed Reader App

This is a very simple app that displays entries from 4 different RSS feeds. The user chooses which feed to display via a menu (accessed and hidden by clicking a hamburger menu icon).


## Running the Tests

To run the Jasmine test suites, open a web browser, select "File," and navigate to the index.html file within the project directory.

## Test Coverage

The tests in feedreader.js cover the following app functionality:

1. The allFeeds variable (the object that holds the names and urls of the 4 feeds that the app reads) is defined.

2. The feed names are defined, not null and not the empty string.

3. The URLs for each feed are defined, not null and not the empty string.

4. The menu (which allows the user to select from among the four feeds) is hidden by default.

5. The menu changes visibility when the menu icon is clicked (i.e., it is hidden by default, but becomes visible when the icon is clicked, and is hidden when the icon is clicked again).

6. There is at least one RSS feed in the feed DOM element. This tests that the asynchronous loadFeed() function is working properly and populating the entry template.

7. When a new feed (i.e., from a different url) is loaded, the content on the page should change.
