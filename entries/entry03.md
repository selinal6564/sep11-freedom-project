# Entry 3
##### 2/6/23

I started to learn how to add **movement** to the sprite and make it jump by tinkering with components found in the [intro](https://kaboomjs.com/doc/intro). One way that I learned to add movement is to make the sprite jump when "space" was pressed. I learned that to make the sprite jump, I needed to use `.jump()`. One challenge was that I realized `.grounded()` was also needed because the sprite needed to stay on the platform so it was ready to jump. Another way that I learned to add movement was to use `.onCollide()`. By using `.onCollide()`, the sprite is able to do a certain action when it collides with another object. Another thing that I learned was how to add **obstacles** for the sprite to jump over. When I was tinkering, I wanted to find a way to have multiple obstacles. One way to do this is to use a [loop](https://kaboomjs.com/#loop):

```
loop(2, () => {
	// add tree
	add([
		rect(40, 64),
		area(),
		outline(1),
		pos(width(), height() - 48),
		origin("botleft"),
		color(255, 180, 255),
		move(LEFT, 240),
		"tree",
	]);
});
```

In this loop, the object will appear every 2 seconds. This works well if I wanted to reuse the same obstacle multiple times.

Next, I plan to learn how to make the sprite move left and right and how a score can be added to the game.

I am currently at **Stage 2: Research the problem** of the Engineering Design Process. In this stage, I am learning my tool and figuring out how a game can be made using Kaboom. For the next stage, I plan on tinkering with my tool more and start thinking about what I will use to make the game.

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)
