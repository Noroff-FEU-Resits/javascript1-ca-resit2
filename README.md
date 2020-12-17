# JavaScript 1 CA Resit 2

## Brief

You will need to create 3 HTML files, `index.html`, `detail.html` and `contact.html` and create and link to a script file for each page.

## Styling
The focus of the CA is on JavaScript, not styling. Yet, as a front-end developer you will always need to produce user-interfaces that make sense and are easy to follow. You will need to provide navigation between the pages.

Both API calls should include a loading indicator.

## Level 1 Process

### index.html

Make a fetch call to the following URL. 

```js
https://t9jt3myad3.execute-api.eu-west-2.amazonaws.com/api/old-games
```

This endpoint will return an array of results. Loop through the results and create HTML for each result.

Display the `name` and `image` of each result in appropriate HTML elements.

Catch any errors and display a message on the page if an error occurs.

Display a loading indicator while the API call is in progress, even if it is just the word "Loading...".


### details.html

Make a fetch call to the following URL. 

```js
https://t9jt3myad3.execute-api.eu-west-2.amazonaws.com/api/old-games/fuzion-frenzy
```

This endpoint will return a single result.

Create HTML and display the following properties:

- name
- image
- released
- rating

Catch any errors and display a message on the page if an error occurs.

Set the title of the page to the `name` property.

Display a loading indicator while the API call is in progress, even if it is just the word "Loading...".

### contact.html

Create a form with the following inputs and validation rules.

- name - required
- email - must have a value and be formatted like an email address
- number of guests - required
- dietary requirements - minimum value of 4 characters.

When the form on this page is submitted, write code to validate the input. If any of the inputs fail validation display an error message for the relevant input.


## Note

- Your code must be properly formatted and your function and variables must be appropriately named.
- Make sure there are no errors in the console.

## Submission

-  Submit the link to your repo on Moodle.