# PA3-Fractals

## Description
This project is base in put in practice our knowledge of recursion function using fractals. This app has different modes wich you can changes using keys and edit some things of the different fractals that the have. 

## Specs

This are the specifications we needed to Implement

### Phase 1 (Suggested Deadline: November 14)
The specs for this phase will act as a warm-up.
• Levels: Create an attribute “levels” which controls the depth of recursion of a fractal. Make it so that pressing “-” decreases the depth of recursion and pressing “=” increases the depth of recursion.
• Coloring Levels: Have each “level” or depth of each of the fractals be drawn in a different color.
• Activate Fractal: Make it so pressing a number will activate a fractal rather than simply switching to it. This will provoke overlapping fractals if more than one are activated at once.

### Phase 2 
The focus of this will be to work with existing classes in a more complex way and refactoring.
• FractalMode: Create an abstract class called FractalMode. This class should have three methods: draw(), getActivate() and setActivate().
• Edit Circles Fractal: Change the Circles fractal so instead of a circle, it is a different shape of your choosing.
• Edit Tree Fractal: Add two more Tree fractals that are smaller in size around the larger existing one.
• Complete Sierpinski: Edit the third fractal so that Sierpinski’s triangle is complete. Hint: There should be three recursive calls instead of two.

### Phase 3
The focus of this phase will be to finish refactoring, add personal flair to the application, and include an animation feature.
• Refactor Fractals: Turn each of the drawMode() methods in OfApp into a Subclass of the abstract class FractalMode. Create an attribute of type vector <FractalMode* >in ofApp. Make it so that pressing an number will “activate” the mode in that position (index) of the vector. For all modes in the vector, if they are activated, they should be drawn on screen. NOTE: After this spec, you should remove all of the drawMode() methods from OfApp.
• New Fractal: Create a new FractalMode of your own design, you may use as many shapes as you please, and it may be as complicated as you wish, however, in each level of recursion, the fractal must implement the same pattern. This spec must be implemented using recursion.
• Animation: Add an animation feature to your application. The feature will work in the following way: by pressing the space bar, the recursion depth will be set to 0 and the animation will be activated. Every certain amount of frames (ticks/updates/draws) the recursion depth will be raised by 1, so that we will see an animation of all the active Fractals growing slowly. The fractals will reach up to level 6 in recursion, then go back down to 0. This will continue until the animation is cancelled by the user by pressing the ‘c’ key.

## Student's Name and email that work on this project:
Mateo I. Muñiz Velázquez:     mateo.muniz@upr.edu
Juan D. Perez Sepúlveda:      juan.perez39@upr.edu     