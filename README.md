# Bubbles
> A simple class to add css bubbles to a DOM element


Have you ever wanted to have a page full of bubbles gracefully floating upwards? Do you want just 1 bubble somewhere important? Adding the bubbles class to your project can do just that! 

![](https://user-images.githubusercontent.com/53430036/82980158-c3704300-9fb6-11ea-8d2e-682e3d67f2ef.png)

## Installation and Usage

Download the app.js file and add it to your HTML project. Wahoo!

```
<script src='app.js'></script>
```

In your console you can test it out by running 

```
makeBubbles()
```
This will add 100 bubbles to the body of your html file. 

## Usage example

However, that probably isn't as useful as adding the number and color of bubbles to the element you want to have bubbles. For this you can simply do the following in your own project

```
const bubble = new Bubble(size, blur%, color(rgb or hex), DOMElement )
bubble.createBubble()
bubble.moveBubble()
```

This will generate a single bubble for you to enjoy! 



## Work In Progress

Still working on making sure bubbles can normally be added to the dom regardless of odd formatting/css constraints

## Meta

Kalen Honeyfield – [@KHoneyfield](https://twitter.com/khoneyfield) – kalenhoneyfield@gmail.com

[KalenHoneyfield@github](https://github.com/kalenhoneyfield/)