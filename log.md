# 100 Days Of Code - Log

### Day 0: March 11, 2022

**Today's Progress**: Built simple chessboard with HTML, CSS. Pulled data from NYT developer API.

**Thoughts:** Good to do some CSS work today. Connecting to the NYT API was straightforward. Starting to think through how to expand on the Book List project for my UW class.

**Link to work:** [Best Books Project JS](https://github.com/RyanOD/Week-8/blob/master/best-books.js)

**Link to work:** [HTML/CSS Chessboard](https://codepen.io/Krumpet/pen/RwxbJPX)

### Day 1: March 12, 2022

**Today's Progress**: Worked on front-end design of NYT API project (codename = SearchTimes). Created helper functions to format book title, author, and description to title case or sentence case. 

**Thoughts:** Initial design came together quickly. Need to better understand how to do visual design outside of VSCode. Struggling with justify-content: space-between on book cover images.

**Link to work:** [Best Books Project JS](https://github.com/RyanOD/Week-8/blob/master/best-books.js)

### Day 2: March 13, 2022

**Today's Progress**: Added logo to NYT API project. Adjusted the positioning of the form labels. Connected to random user API for home page "reviews" section.

**Thoughts:** It is getting so, so easy to work with APIs. Feeling good about such a new skill.

**Link to work:** [Best Books Project JS](https://github.com/RyanOD/Week-8/blob/master/best-books.js)

### Day 3: March 14, 2022

**Today's Progress**: Built out /books.html page to display data received from user request. Books list pulled from NYT API is used to determine ISBN of each book which is used to pull book covers from Open Library API.

**Thoughts:** Had to update form to send form fields to new page via a GET request. This was simple, but different from what we've been doing in class. Required the following JS to retrieve the query string parameters from the URL.

    const urlParams = new URLSearchParams(window.location.search)

**Link to work:** [Best Books Project JS](https://github.com/RyanOD/Week-8/blob/master/best-books.js)