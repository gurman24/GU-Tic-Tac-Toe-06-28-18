by Gregory Urman

www.linkedin.com/in/gregoryurman



# GU-Tic-Tac-Toe-06-28-18



In this project, we will explore Tic-Tac-Toe as a simple AI and reiforcment learning algorithm example. Unlike "Multi-Armed Bandit," 
Tic-Tac-Toe is much simpler and involves much less variables. One of the biggest determining factors in the latter is that the number of all possible states for the agent and the environment CAN BE enumerated! (in other words all of it fits into memory). What does that look like? 

1) There are 9 possible positions in the game --> because of 9 cells total
2) Each of the positions can only have 3 possible values -- nothing, X, or O
3) So, the number of states in the environment is 3 ^9 (3 to the 9th power) or 19683


Additionally, what makes the Tic-Tack-Toe program different than Multi-Armed Bandit is that there can only be TWO POSSIBLE AGENTS (programs or algorithms that make decisions on their own based on their pre-programming -- in other words Machine Learning!) At least one Agent has the be the AI itself. The other Agent can be a human being or another pre-programmed AI Agent. That means you can play Agent against Agent AKA watch the computer play itself. ... One of the interesting things about doing that would be to mess around with the Learning Rate for each Agent to see what difference that makes. ... It is also very important to mention that Tic-Tac-Toe, like Multi-Armed Bandit, also uses the Epsilon-Greedy algorithm (in other words explore vs. exploit, look that up separately if interested, it's a simple but very important idea). 

---------------------------------------------------------------------------------------------------------------------------------

TO DIGRESS, this is a very important concept in how Tic-Tac-Toe works as wells how many other concepts in the area of Reinforcement Learning work:

![agent and environment chart](https://user-images.githubusercontent.com/22970879/42120041-d7145168-7bd1-11e8-8f11-42546269f56e.png)

The above chart shows how the Agent and the Environment work in a look -- they are interrelated and they create a long, or maybe even infinite, self-updating process through which reinforcement learning takes place. This kind of model does come with some assumptions that can be explored independently if the reader chooses to do so. 

----------------------------------------------------------------------------------------------------------------------------------

Back on topic: 

Since the entire code file is superfluous here to understand the project, I'm adding only a SNIPPET. What this is really showing is just some of the coding it takes to make this kind of Python code also known as Jupyter Notebook code work properly:

![tic-tac-toe code snippets](https://user-images.githubusercontent.com/22970879/42120292-5779abec-7bd6-11e8-8e1f-ce5503a8d922.png)

...

What's below is a picture of the moves in sequence the Agent made to beat the human player. Remember that since all the moves are enumerated, it would be very difficult or even impossible to beat the Tic-Tac-Toe agent, but you can play it to a draw

![tic-tac-toe moves sequence](https://user-images.githubusercontent.com/22970879/42120298-6e82fd48-7bd6-11e8-9ca7-f44cdd797d98.png)
...

# Conclusion #

...





