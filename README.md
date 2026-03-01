# 5010Assignment05-Noise

## Concept: Rock Climbing Route Setting

Based of the practice of route setting for indoor climbing gyms. The player and program take turns placing climbing holds on a wall, mimicking creating a climbing route.

### Reflection

This project has concluded in a strange way in that I felt that I fully suceeded in some areas, and fully didn't in others. 

To start with the aspects I'm proud of, I really like how the code works overall. It does the thing I wanted it to do, even if that didn't fully align with the goals of the assignment. I'm also proud I figured out how to use classes! I think I have a much stronger understanding of how methods and classes work, and why they are important. Altering the code I had already created to work as a class in a seperate method was hard but worth while. 

One area I didn't suceed in was working with arrays. I feel like the functionaliy is close, but my understanding is not. I hope I'll have more opportunity to explore that aspect of coding. I also didn't really use noise in my project. It does incorperaet randomness, but not noise and particles. 

Overall a good learning experience.


### Plain English Directions

1. Draw the rock wall as the background.
    1. Draw a grey rectangle of any dimension. Add a slight gradient from top -> bottom, light -> dark
    2. Divide the canvas into a set of vertical collums of randomized width
    3. Within each collum, draw a segmented zig-zagging line from top to bottom, representing the panels of the climbing wall. the length and angle of the line segments is random constrained by the collums
4. Create the hold generator
    1. Choose a color for the holds
    2. Generate a n-gon with random amount of sides
    3. Offset vertexes by a random amount
    4. Constrain n-gon within two cocentric circles 
6. Create a start hold in the bottom center of the wall. 
7. The player places a hold on the wall based on their cursor location with the constraint that it must be within a certain radius of the start hold. 
8. The program places the next hold, following the same rules.
9. This repeates until 10 total holds are placed
