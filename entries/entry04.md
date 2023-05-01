# Entry 4
##### 3/13/23

In Kaboom, I started to learn how to make a sprite move left and right and up and down. By reading the documentation and tinkering, I realized that I could use `onKeyDown()` to press the key and make the sprite move in any direction. I also learned that if I wanted to try to make the sprite move, I also needed to create a variable for speed. I learned that by putting the speed as positive or negative in the x value will make the sprite move backward or forward, while putting the speed in the y value will make the sprite move either up or down. Another thing that I have been learning is how to add a score. I looked through the documentation and realized that I could use `onUpdate()`to update the score everytime. I also learned that the `text()` component can be used to show the score in the game.

My partner and I have made some progress on our MVP. We have added a sprite and movement to it. By using `onKeyPress`, we were able to make the sprite jump. We also used `onKeyDown` to make the sprite move right and left and up and down. This was how we added movement:

```
    onKeyDown("right", () => {
      mc.move(-SPEED, 0)
    })

    onKeyDown("left", () => {
      mc.move(SPEED, 0)
    })
```

We changed the movement of the sprite by making the speed negative when the right key is pressed, so that it would move backwards and the speed positive when the left key is pressed, so that it would move forward.

I am currently on Stage 3: Brainstorm possible solutions and Stage 4: Plan the most promising solution of the Engineering Design Process. In this stage, I am still learning my tool and finding ways that I can make a game with Kaboom. I am also starting to make a game and seeing what should be incorporated into the game. For the next stage, I plan to think more about what to add to the game.

One skill that I grew in is attention to detail because I realized that by changing small things, it can impact how the game functions. For example, at first I was confused on why putting the speed in the x value would move the sprite left and right and not up and down. Later I realized that by putting it in the x value, it changes the value in the x axis, which goes from left to right. I also realized that if the speed is negative, it changes where the sprite will move. Another skill that I grew in is how to learn because the components that I learned this time in Kaboom were new compared to ones I learned last time. I was able to learn how I could make the sprite move in more ways, like right and left and up and down.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)