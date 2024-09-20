# Interactive Particle Explosion Simulation

This project is a simple interactive particle explosion simulation built using **HTML5 Canvas** and **D3.js**. The simulation creates a burst of particles whenever the user clicks anywhere on the screen, generating colorful explosions with random velocities and fading effects.

## Features
- Click anywhere on the canvas to create a particle explosion.
- The particles move in random directions and fade out over time.
- Supports dynamic resizing of the canvas to fit the browser window.
- Limited to a maximum of 1000 particles on screen at any time to maintain performance.
- Uses D3.js for color scheme and event handling.

## Technologies
- **HTML5 Canvas**: Used for rendering the particles and handling the animations.
- **D3.js**: Used to handle the mouse click events and color generation (`d3.schemeCategory10`).

## How to Run
1. Download or clone the repository.
2. Open the `index.html` file in any modern web browser.
3. Click anywhere on the canvas to see the particle explosion in action.

## File Structure
- `index.html`: The main file that contains the HTML, CSS, and JavaScript for the simulation.

## Demo
You can view a live demo of the simulation on **GitHub Pages** by visiting:
[https://your-username.github.io/particle-explosion-animation/](https://your-username.github.io/particle-explosion-animation/)

## Customization
You can customize the following aspects of the simulation:
- **Particle Count**: Modify the `numParticles` variable in the `createExplosion()` function to change the number of particles generated per explosion.
- **Particle Colors**: Customize the color scheme by changing the `d3.schemeCategory10` array.
- **Particle Size**: Modify the value passed to `context.arc()` to adjust the size of each particle.
- **Max Particles**: Adjust the `maxParticles` constant to limit the total number of particles on the screen.

## License
This project is licensed under the MIT License. Feel free to use and modify the code.
