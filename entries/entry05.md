# Entry 5
##### 4/17/23

In Kaboom, I started to learn how to create a map for a game. This video was helpful for me because it helped me understand what the symbols in the map represent. At first, I used objects and a loop to create obstacles. I later realized that a more complex map could be created by adding levels and using symbols. From the video, I learned that I could use symbols that are defined to create a map. For example, I learned that symbols could be defined like this:

```
"$": () => [
        sprite("coin"),
        area(),
        pos(0, -9),
```

This would mean that everytime the symbol "$" was used, it would create a coin in the map.

My partner and I are close to finishing our MVP. We have added a new map to our game. This was the map that we added:

```
map = [
  "                                ",
  "                                ",
  "                                ",
  "           ^         ^          ",
  "                  ===           ",
  "        ===                     ",
  "           ^                    ",
  "                                ",
  "========   =======    ==========",
]
```

In our map, the symbol "=" is used to represent the grass, which is the obstacle course. We also used the symbol "^" to create an enemy that the sprite has to avoid in order to reach the end. We are still working on how to make the sprite lose when it touches the enemy.

I am currently on Stage 4: Plan the most promising solution and Stage 5: Create a prototype of the Engineering Design Process. In this stage, I am still learning my tool to see what I want to add to the game and have already started creating the game. For the next stage, I plan to add more to my game and see how I could improve it.

One skill that I grew in is communication because my partner and I had to communicate and put our ideas together to create the game. We had different ideas, so we had to find how we wanted to input both our ideas together and also assign who was doing which task. Another skill that I grew in is how to learn because I learned something new from Kaboom that I wanted to incorporate into our game. I learned how to make a map and how to include different obstacles in it. I think this will help me make more levels for the game.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)