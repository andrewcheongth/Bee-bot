# Bee-bot
<ins>Background</ins>\
This program was made to fulfil the requirements of a postgraduate coursework.

<ins>Description</ins>\
Python program to find the sequence of actions allowing the Bee-bot to go from the initial state to the final state.

Bee-bot is a programmable robot used to introduce children to control, directional language and programming. It allows them to learn the importance of sequences of accurate instructions. The robot has four different buttons: “Up” to move forward, “Down” to move backward, “Left” to turn left (90°) and “Right” to turn right (90°). Children can create a sequence of actions using the four different buttons in order to create a plan for the robot to reach the destination. Once the plan is created, they can click on the button “Go” so the robot can start moving.

<ins>Requirements</ins>
1. Choose and implement a formalism to represent all possible states or what is known as the state representation; this includes the initial state and the final state.
2. Define and implement the list of possible actions at each time and a validation function that will check whether or not a state / action is valid.
3. Write a function that will allow to generate the map automatically. The map should contain two type of cells. White cells are empty cells where the robot is allowed to move in and out these cells, and other cells that are considered as obstacles where the robot is not allowed to go through. The dimensions of the map should be chosen by the user, and they must be greater than 10. Feel free to use any colour or character / symbol for the graphical representation.
4. Implement the algorithm Depth-First-Search allowing the robot to find the path to the final state and display the path or the sequence of actions to be executed by the robot to go from the initial state to the final state.
5. Implement the algorithm A* allowing the robot to find the optimal path and display the optimal path or the sequence of actions to be executed by the robot to go from the initial state to the final state.
6. Compare the two solutions (Q4 and Q5) and analyse the results based on two criteria: Speed and efficiency.
