# Exercises

## Problem solving cardio
Lets exercise our problem solving abilities!

![mind exercise](https://media.giphy.com/media/l41m04gr7tRet7Uas/giphy.gif)

### Find the shortest word
Write a function that finds the shortest word of an array of words

```js
const danishWords = ['bil', 'plante', 'kaffe', 'bog', 'ø', 'planetarium'];
notThisFunctionName(danishWords); // returns 'ø'
```


## Simple eventlistener
When clicking a button, change the text on the button to say "Button clicked"


## Favorite dishes
Create an array of strings with your favorite dishes.

With js select a `ul` in the DOM. You add the `ul` to the html file. 

Now loop through each element of the favorite dishes array, you create an `li` element and set the text to the favorite dish.

Then append the `li` element to the `ul` element.

## Podcast

```js
const podcasts = [{
        name: 'The mystery om of Johan Klausen Varbourg',
        imageUrl: 'https://picsum.photos/536/354'
    },
    {
        name: 'Tips about dogs with small legs',
        imageUrl: 'https://picsum.photos/536/354'
    },
    {
        name: 'You, me, we and us',
        imageUrl: 'https://picsum.photos/536/354'
    },
    {
        name: 'Breakfast news - Dinner edition'
    }
];
```
1. Create a `ul`
2. Loop through the podcasts
3. For every podast:
   1. Creat an `li`
   2. Create an `h1` element
   3. Change the innerHTML of hte `h1` to equal the name of the current podcast
   4. Append the `h1` to the `li`
   5. Now add an image to the `li` with the `src` set to the `imageUrl`. But only if the `imageUrl` key exists on the object!
4. Append the `li` to the `ul`

## Image inserter

Create a function that has two parameters: `imageUrl` and `elementToAppendImageTo`. The function should create an `img` tag using the `imageUrl` parameter. The function should then append the `img` to the `elementToAppendImageTo` - html element.

```js
// Should append a img tag to the body with the picture from 'https://picsum.photos/536/354'
notThisFunctionName('https://picsum.photos/536/354', document.querySelector('body'));

```

## Light mode dark mode
Clicking a button should toggle the background color of the body and the text color in the page.
If the background is white and the text is black, then clicking the button will make the background dark and the text white and vice versa

*Optional* also make the text on the button change. 

## Spirit animal name generator
Let's create a page where **a user writes his name** in an input element. The user then clicks a button. The user will now **receive a spirit animal name**, fx Benjamin - The fullmoon wolf.

### Markup time!
Create an input element, a button and a tag to display the spirit animal into.

### Setting up the events
When the user clicks the button, get the name the user wrote in the input field. 

### Spirit animal part
Now we can get the users name, next step is to **add the spirit animal string** and display that the users name, a dash and then the spirit animal. Fx Name: Peter: Peter - The crying butterfly. 
For creating the spirit animal create an array with 10 string representing spirit animals. Now get a random item in the array that will represent the spirit animal.

### New spirit animal
Now a user tells us that he wants a new spirit animal. No problem we say. Let's create functionality where a user can press a button and then get a new spirit animal.

### No input
What if the user clicks the generate new spirit animal and there is no text in the input?

### Event types - *Optional and a little tricky*
Give the user the possibility to select **when the spirit animal should be created**. Should it be when the user clicks the button or when the user hovers the input field or when text is written in the input field? 

How can we give a user multiple options to select from in html? Maybe time for google!

An example is: A user select that she only wants to generate a spirit animal when the input is hovered. That means that if the user writes her name in the input and clicks the button nothing happens. BUT when she hovers the input, NOW a new spirit animal is generated.

![Spiritanimal](https://media.giphy.com/media/IMSq59ySKydYQ/giphy.gif)

