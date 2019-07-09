# Ping Pong

## During the workshop we're going to work together to build ping pong 🏓

First we'll start by creating the different files, and displaying our canvas element. After that we'll practice using canvas to draw shapes and change their colours and positions.

Then we're ready to start! 

Let's add a start button with an onclick function - soon you'll see why. We'll also add a drawing loop function that will be called on each frame.

Next, we're going to create the paddles. We'll need one for each player. You can play around with the coordinates to see exactly where you want them to be positioned. We'll draw the paddles inside the onclick function when we click the start button. Now when you click the start button you'll be able to see the paddles. 

The next step will be to add the keydown event listener to the paddles to allow the player to move. Player 1 will use two letter keys and player two will use the arrow keys. We'll add the paddles into our drawing loop so that you can see the movements.


Now we need the ball! We'll draw the ball and then we'll need to add it to the start function and to the drawing loop. Next, we'll add speed and direction to the ball. 

It's looking good, but now we need to control for boundaries. First we'll create a function that detects when the ball hits the top or bottom so that we can change the direction of the ball. We'll need to add this to our drawing loop too. 

Once we have that working we can create another function to check to see if the ball hits the paddle. Let's add that to the drawing loop and then we have a working version of ping pong!! 

### BONUS FEATURES
 Found this easy and want to improve the game? Here are a few suggestions on features to add: 
 - counting points 
 - winning the game when you reach 5 points 
 - another level, maybe the ball goes faster or the paddles are smaller. 
 - adding sound effects for when the ball hits the paddle or goes off screen 

 Have fun 🎉🎉

