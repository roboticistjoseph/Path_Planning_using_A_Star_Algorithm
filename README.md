-----------------------------------------------------------------------------------------------------------------
ENPM 661- Planning for Autonomous Robots;
-----------------------------------------------------------------------------------------------------------------

Team Members:

Name: Bharadwaj Chukkala
UID: 118341705

Name: Joseph Pranadeer Reddy Katakam
UID: 117517958

------------------------------------------------------------------------------------------------------------------

Project 3, Phase 1: Implementation of A Star Algorithm for a Rigid Body Robot

GitHub Link: https://github.com/roboticistjoseph/a_star_algorithm

Video Drive Link: https://drive.google.com/drive/folders/1o5HvvbLppkN7Pmss0JQCHE8xHmnWHCw_?usp=sharing

Code:
- Code consists of: 'Generating an Obstacle Map, 'Movement in 5 Directions', 'Using Search Algorithm and Back Tracking' and 'Visualizing the Tracked Path'
- The Search Algorithm used here is ' A Star Algorithm' to reach end goal and obtain the path.
- The code has been delineated very clearly in the comments provided in the Code.

Dependencies:
- python 3.9 (works for any python 3 version)
- Python running IDE. (I used PyCharm IDE to program the Code and Execute the Code)
- Libraries: numpy, matplotlib.pyplot, heapq, time

P.S. The visualization of the plotting is not smooth in spyder or Visual Studio. Use Pycharm or such IDE's.

Instructions to Run the Code:

To get the Output (without Visualization)
- Open the 'astar-pathplanning-Joseph-Katakam.py' file in any IDE. (I used PyCharm)
- Run the Program
- In the Console, the program asks for:
|-- The Obstacle Clearance and Robot Radius
|-- Robot Step Size and 
'-- The x and y coordinates of Start and Goal Node. 
- Enter as prompted. Ex: Clearance: 5; Robot Radius: 10; Step size: 1; Start: 50, 50; Initial Theta: 30; Goal: 150, 150; Final Theta: 30.
- The Output Plot with planned Path should be Visible.

To get the Output (with Visualization)
- Open the 'astar-pathplanning-Joseph-Katakam.py' file in any IDE. (I used PyCharm)
- UnComment the line used for Visualization i.e. '309', which says- "plt.pause(0.000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001)"
- Run the Program
- In the Console, the program asks for:
|-- The Obstacle Clearance and Robot Radius
|-- Robot Step Size and 
'-- The x and y coordinates of Start and Goal Node. 
- Enter as prompted. Ex: Clearance: 5; Robot Radius: 10; Step size: 1; Start: 50 50; Initial Theta: 30; Goal: 150 150; Final Theta: 30.
- The Output Plot with planned Path should be Visible.

Understanding the Output Plot
- The Robot movable space is shown in White Color
- The Pixels in Blue are the Obstacles.
- The Pixels in Cyan is the Clearance Space.
- The explored path is marked by Green color.
- The Planned Path is shown by Red Dotted Lines.
