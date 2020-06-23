# Additional Bonus Labs

## Bonus - React Cities

Convert the following [CodePen](https://codepen.io/jkeohan/pen/850f8454693590e9772f8d0f6c2f44c8) into a React app.  Create the following Components and organize based on the below hierarchy:

- App
  - Form
  - SmallImage
  - LargeImage
 
Add an onClick event to each SmallImage that lifts state to App and updates state and reassigns the image src url to the LargeImage. 
 
Add an onChange event to the Form that allows the user to add an image url.  The Form will pass that url to App which will then render it as an additional SmallImage Component.

## Bonus - ColorSwitcher

Convert the following [CodePen](https://codepen.io/jkeohan/pen/abvjvpr?editors=1010) into a React app.  Create the following Components and organize based on the below hierarchy:

- App
  - Form
  - ColorList
  - ColorListItem
 
Add an onClick event to each ColorListIttem that lifts state to App and updates the background color of the app to be the color of the item that was clicked.
 
Add an onChange event to the Form that allows the user to add a color.  The Form will pass that url to App which will then render it as an additional ColorListItem.

## Bonus - Traffic Light

Convert the following [CodePen](https://codepen.io/jkeohan/pen/MWYEyMV?editors=1010) into a React app.  Create the following Components and and organize based on the below hierarchy:

- App
  - Bulbs
  - Buttons
  
Add a click event to Buttons that lifts state to App and updates the Bulbs so that only the chosen Bulb is on and all other Bulbs are set to black. 

## Bonus - Memory Game

Convert the following [CodePen](https://codepen.io/jkeohan/pen/opvVGN?editors=0010) into a React App. Create the following Components and and organize based on the below hierarchy:

- App
  - Cards

Add a click event to the Cards assigns the card its card image and lifts state to the App Component that is used to determine the winning/loosing logic. 

# API Specific

## Bonus - Random Taco

- Use fetch to the below api to render the view of a random taco. No styling needed!

```js
   fetch('http://taco-randomizer.herokuapp.com/random/?full-tack=true')
```

- Create a button to render another random fresh taco
- Add some styling
![screen shot](https://i.imgur.com/1HbPnjB.png)


## Bonus - News API

[News Api](https://git.generalassemb.ly/SEIR-526/react-news)

 
