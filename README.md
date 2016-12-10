# Feedreader Testing
## Introduction
The repository contains the required files and folders for the Feedreader Testing Project.

## Objectives
*  Write effective tests requires analyzing multiple aspects of a web-based application that reads RSS feeds including the HTML, CSS and JavaScript.
* Write test suites using Jasmine.

## Installation
* Clone,download or fork the repository from [here](https://github.com/Sheethal7/frontend-nanodegree-feedreader-testing)
* Open index.html in any browser of your choice

## Tests
#### Test suite: RSS Feeds
* test to make sure that the 'allFeeds' variable has been defined and that it is not empty.
* test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
* test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
#### Test suite: The menu
* test that ensures the menu element is hidden by default.
* test that ensures the menu changes visibility when the menu icon is clicked.
#### Test suite: Initial Entries
* test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
#### Test suite: New Feed Selection
* test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.