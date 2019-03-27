Using object oriented programming and vector math, I created a perlin noise flow field. The flow field
generates a 2D array filled with vectors that have been created using perlin noise. While working on the 
project, I found multiple properties of the flow field that drastically changed the behavior of the flow
field. I took these properties and created a UI that allows a user to change them. Below are the fields
that the user can change:

Input Fields:
    1. Alpha Value: The alpha value of the particles in the flow field. Uses integer values.
    
    2. Vector Field Offset: The vector field offset controls how drastic the vector field changes over time.
    It is best to use values between 0 and 1. Uses float values.

    3. Noise Scale: The noise scale to be applied to creating the vectors of the vector field. Uses float values.

    4. Stroke Weight: The stroke weight of the particles in the flow field. Uses integer values.

    5. Vector Magnitude: The strength of the vectors within the vector field. The higher the value the greater
    the directional effect the vectors have on the particles in the flow field. Uses float values.

    6. Number Of Particles: The numebr of particles that are follow the vector field in the flow field. When set,
    the program will clear the screen and create a new particles array. Uses integer values.

    7. Size of Vector Field Grid: The size of the 2D vector field that the particles follow. When set, the program
    will set clear the screen, change the noise seed value, and create a 2D vector field.

Buttons:
    1. Submit Button: When clicked, it will parse the input fields and update the properties of the perlin noise flow
    field.

    2. Clear Button: Clears the screen with the current background color.

    3. Reset Button: Resets the perlin noise flow field to its default values.

Radio Buttons:
    1. Black Background: Changes the color mode to RGB, background to black, and sets the particle color to white.

    2. HSB with Black Background: Changes the color mode to HSB, background to black, and sets the particle color to white.

    3. White Background: Changes the color mode to RGB, background to white, and sets the particle color to black.

    4. HSB with White Background: Changes the color mode to HSB, background to white, and sets the particle color to black.

NOTE: Best to have the web browser at 100% zoom and full screen.