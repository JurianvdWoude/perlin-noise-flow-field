# Perlin noise flow field

This project is a a visualization of Perlin noise in 2D as a flow field using p5.js, 
a JavaScript library for creating graphics and interactive experiences.
You can find more information on what Perlin noise is on [wikipedia](https://en.wikipedia.org/wiki/Perlin_noise).

## Getting started

To get started with this project, you will need to have a basic understanding of JavaScript and the p5.js library. 
If you are new to p5.js, you may want to check out the [p5.js website](https://p5js.org/) and the [p5.js reference](https://www.p5js.org/reference/) for more information.

To run this project, you will need a web browser that supports the canvas element and JavaScript.

## Running the program

To run the program, simply open the `index.html` file in your web browser. 
You should see the Flow field displayed in the canvas. 

## Description

Perlin noise is a type of gradient noise developed by Ken Perlin in the 1980s. It is often used to generate natural-looking patterns, such as clouds, terrain, and other organic shapes.

In the context of a flow map, Perlin noise can be used to create a flow field, which is a 2D array of vectors that can be used to control the movement of objects in a simulation. Each element in the array represents a position in the flow field, and the vector at that position indicates the direction and magnitude of the flow at that point.

To create a Perlin noise flow map, you can use a Perlin noise function to generate a noise field, and then use the values in the noise field to set the direction and magnitude of the vectors in the flow field. The Perlin noise function will output values that vary smoothly across the noise field, which can be used to create a flow that appears to be smoothly flowing and changing over time.

There are many ways to use Perlin noise flow maps, including for simulations of fluids, particle systems, and other types of motion. They are particularly useful for creating natural-looking motion that is difficult to achieve with other techniques.
