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

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)