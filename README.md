# Summary
I have created this game as part of my Software Architecture module while attending Salford University.
I fell in love with Design Patterns when creating this game and will definitely continue to improve my understanding and knowledge about it, and the other areas within the module.
  
Although the game runs slower than I would like, I am very proud of the progress I have made within my degree and I feel like this game expresses how willing I am to apply new information to a type of project I have never attempted before. I would also like to note the graphics and artwork was created by me using Adobe Illustrator and other similar products.

# Instructions
The homescreen briefly explains the objective of the game - the Lifecycle - but more details are included below.

You will spawn as an Egg that can move around the screen. While an Egg, you will have to avoid contact with your natural predator - the Ladybug.
If you survive long enough you will evolve into a graceful caterpillar where you will no longer be affected by the dreaded Ladybug, but shortly after you evolve the environment will evolve too and the ladybugs will be replaced with birds - your new natural predator.
Finally you will evolve into a Butterfly where you will have to avoid being eaten by frogs.

Be warned, as you evolve the enemies will evolve too, increasing their speed to try and eat you.
Use the WASD keys to move around and avoid your natural predator.

# Screens

### Main Screen
The main screen doubles as an instruction page, briefly explaining the rules of the game.

### Win Screen
Congratulations, you've won the game.

### Lose Screen
If you were hit, you will have the option of quitting the game or to view the collision that caught you.

# Images
<img src="https://github.com/C0dio/Java-Game/assets/68840768/d77ae655-f109-4810-ae8a-f6656fc466b6" width="300" />
<img src="https://github.com/C0dio/Java-Game/assets/68840768/bd45684e-4a35-41b5-8b7b-019c13d1bdd1" width="300" />
<img src="https://github.com/C0dio/Java-Game/assets/68840768/a3dab08e-b920-407d-b44f-94f3a16b10dd" width="300" />

# Design Patterns
This project was designed alongside the Software Architecures module for Salford University: as such, design patterns were encouraged where possible.

1. **Object Pool**; to limit the number of enemies on a page,
2. **Singleton**; for the JavaFX windows to easily access and switch between screens,
3. **Abstract Factory**; to build the enemies,
4. **Visitor**; to handle the evolution of the enemies,
5. **Null Object**; to handle the final stage of evolution for fully evolved enemies which try to evolve before the time runs out,
6. **Proxy**; used on the "view the collision" screen to render enemies without rendering their behaviour.
