# Entry 5
##### 4/23/23

##### The developement of learning my tool and the finalization of our MVP

Hello! This is my fifth blog entry and in today's blog entry, I will be able to talk and explain what I worked on and the build up and creation of my team and I's Freedom Project MVP. Incase you are unsure or think by MVP I am talking about a most valuable player, I am actually refering to "Minimum Viable Product"; by this I mean the most simple outcome of our ideas. This is the goal of our progress and what we are working for.

When thinking and wraping up our ideas for our MVP, we came up with the basics of our project and what we must accomplish first. In my group which consists or me, Safe, and Jaiden, we all worked seperatly but united our ideas and our knowledge after every week. The basics that we knew we had to accomplish before anything else, was fully understanding our tool, having a start and end to our game, and having a layout with different values giving it a purpose. Although our understanding of our tool is still questionable, we were able to complete the MVP within the time recieved. 

##### My personal progress/ what I helped with

In our MVP, I supported the creation of our controls of the game and the layout. The thing I began to focus on first for our MVP was actually being able to play the game and move a created caracter. At first while looking for how to move a character, I was able to find the basic code needed in order to successfully move our character however, Jaiden assisted me with filling the gaps to make the code work. Here is the final outcome of our code:


  onKeyDown("left", () => {
		player.move(-MOVE_SPEED, 0)
	})

	onKeyDown("right", () => {
		player.move(MOVE_SPEED, 0)
	})

	onKeyPress("down", () => {
		player.weight = 3
	})

	onKeyRelease("down", () => {
		player.weight = 1
	})
  
  
  This code successfully makes our character move and pass through the levels without hesitating. Another Impact I had into the MVP of our project, was creating the layout of our game. I created a simple yet effective format for our game which would be one of the levels for our code. The downside of my cold, was the time it took for me to make it! Safe got to the layout before me and once I was able to hare it to my group, the layout wa already in effect and was no longer needed.
  

#### Takeaways and self-reflection 

One of the things I learned from completing the MVP of our Freedom Project, was that communication is key. Because of somewhat of a lack of communication, me and my team could have organized ourselves better in order to not have to give some people more work than others. Also, another piece of self reflection is that time manegment should be what I work on from now on! I lack time management and that could be fatal when wanting to complete somethign important in a given ammount of time. Thank you! for taking time to read my blog entery #5 and hopefully you enjoyed my progress and developement!

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
