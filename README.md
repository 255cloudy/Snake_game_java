# WELCOME TO NYOKS.

## Nyoks is a recreation of the popular old-school arcade game Snake Xenzia with a mordern touch including colors, sound effects and textures hopefully :smiley: .

# TECHNOLOGY STACK.

To increase the accesibility and ease of use of this beutiful game we have made the decision to stick to native java classes/libraries. They are:
    
    1. Java swing - this is used to create and manage the windows. It was choosen because 
        it is cross platform and easy to use.
    2. java.awt.* - this contains a collection of classes that allows us to easily get the          user input, manage and draw 2D objects such as polygons and images easily.  


# CLASSES.

1. ## Game class.

This is the main class which is responsible for:
    - creating and initialising the window.
    - Keeping track of the game state ie paused, game over etc and controlling it.
    - Initialising the core classes such as the GameController to support the game.

2. ## GameController class.

Responsibilities:
    - initialising the game area within the window provided.
    - initialising the snake and apples.
    - acts as the main game loop ie supports the rendering process for all game objects.

3. ## Snake class.

Responsibilities:
    - keep track of snake properties as a whole.
    - keep track of the snake segment objects.
    - identify and keep track of the head of the snake.
    - Store state information on the turns that the snake has made.

4. ## Segment class.

These are the various sections that the snake will be composed of. 
Responsibilites:
    - keep track of the position of the segments.
    - contains the logic required render the segment. Every segment contains all 
        the information required to render itself. 
