# Task 5: Adding Tasks

## Description

For this task, we'll be adding the current date to be displayed on our To Do application using JavaScript's 
built-in Date object.

## Walkthrough

### Step 1: The Setup

1. Make sure there is a span element with a unique id attribute in your HTML that can will display the current time on the page.
2. Inside index.js, use a query selector to select this span element and save it to a variable called dateElement.

### Step 2: Finding and Displaying the Date
> #### Useful Resources for this step
> - [MDN Date Object Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)
> - [W3Schools Examples of the Date Object](https://www.w3schools.com/js/js_dates.asp)

1. Inside index.js, create a new Date object. 
2. Console.log the Date object you just created to see what you have to work with. *Make sure you create the Date object as soon as the page loads, not inside an event listener.
3. Use independent research to find how to seperate just the day, month and year of this Date. 
4. Display the day, month and year in the span element we selected in our code above using our innerHTML property in a way that is easy for the user to read.

## Results

We've now found today's date using the built-in Date object and displayed the current day, month and year on our task planner.

## Example

Stuck? Check out the provided example in the [example/](example/) folder!

## Assessment

This will be assessed as part of [Sprint 2](https://docs.google.com/spreadsheets/d/1oKMVurjg8SW7cRU4-NwUxTxSvav4l5_W7yvDCHd3DKo/edit?usp=sharing) 
