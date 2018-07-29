# Feed Reader Testing
This project tests your ability to create tests to predict if your code will run smoothly without errors using Jasmine.

## Installation Instructions

Step 1: Download the project on [Github](https://github.com/udacity/frontend-nanodegree-feedreader)

Step 2: Open the index file in your browser.

Step 3: Review JS, CSS, and HTML files to determine functionality.

Step 4: Replace TODO comments with your code in feedreader.js.

Step 5: Determine if specs pass or fail in Jasmine 2.1.2.

Step 6: Your tests are completed and working correctly once all specs pass and turn green.

## Step by Step - Tests to Create

1. Create a test to make sure that the allFeeds variable has been defined and that it is not empty.
2. Create a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
3. Create a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
4. Create a test that ensures the menu element is hidden by default
5. Create a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6. Create a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. Remember, loadFeed() is asynchronous so this test will require the use of Jasmine's beforeEach and asynchronous done() function.
7. Create a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes. Remember, loadFeed() is asynchronous.

## Sources
If you run into any road blocks, [Matthew Cranford](https://matthewcranford.com) does an excellent job teaching the fundamentals on how to complete this project. [Part 4](https://matthewcranford.com/feed-reader-walkthrough-part-4-async-tests/) on Async testing was very helpful to me, he helped me understand how to code the New Feed test suite.