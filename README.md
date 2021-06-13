# Covid_Map_Simulation
This program tells you the shortest path from your initial position
to the nearest quarantine place accoring to the user entered specifications
described below.
First, it will ask you to enter the number of rows and columns.
Please only enter integer values there.
Then it will ask you to enter number of Quarantine cells. Enter only
integer value.
Then enter cell number you want as Quarantine Places.
Same thing for Vaccine Spot and Playground.
Please don't enter a cell number twice after it has already been 
occupied before. This might give an error or incorrect result.
After this, you will see a map on console with cell ids and node ids and 
cells that will indicate the quarantine places, vaccine spots 
and playgrounds you entered before.
You will also see an x and y axis along with map.
After this, it will prompt you to enter x and y values of start and 
goal point. 
You can enter any value. If you enter values outside the range, it 
will prompt again. You only have two chances. It will result in 
error if you enter outside range value twice.
You values might be modified according to the Role.
You will see your modified x and y values so 
that they are at top right of a cell only.
If you entered your start point that is already in position of your 
Role (Quarantine Place), you will 
not get any path or cost.
If you entered your goal point that is meant for you (Quarantine),
you will get an optimal path from your 
start point to your end point along with cost along with matplotlib GUI
that shows path on the map
However, if you entered a goal point not meant for you, the program will
find the nearest point meant and and you will get path and cost to that
point along with matplotlib GUI that shows path on the map

Libraries Used : Matplotlib Only

Program will end with a thank you message

                                      
