# Project Overview

Test suites testing the following subjects.

1. Open index.html
2. A test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
3. A test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
4. Write a new test suite named "The menu".
5. A test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
6. A test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
7. A test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test wil require the use of Jasmine's beforeEach and asynchronous done() function.
8. A test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.
