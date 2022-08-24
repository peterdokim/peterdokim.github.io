Install Anaconda on your computer.
Details could be found here.<br>
[Link to the conda install](https://ieworld.tistory.com/12)<br>
Activate conda by ```conda activate```.
Pull the file from the github repository by ```git pull origin develop``` from the terminal, and the file path you wish to clone it to.
Type in command ```python main.py``` from the terminal.<br>
GUI would pop up that will look like this

![Screenshot from 2022-08-24 10-57-46](https://user-images.githubusercontent.com/61016872/186340951-3af00c85-8a2c-43dc-baa7-d23b86168248.png)<br>
Select the ground truth and the target file by add button at the bottom of each list. <br>
Push the convert button to proceed with reading the ground truth and the target file. <br>
Afterwards, you will be able to generate graphs of different shapes.<br>
Projection trajectory shows the trajectory of the movement of the vehicles. Ground truth vehicle is the one we pu the gps on, object data is the data we received from each of the lidar sensor that we put on the vehicle.<br>
Lateral longitudinal error data has been implemented from the data we measured from projection trajectory and the speed quiver plot. <br>
I have noticed that what is lacking is the quantitative data analysis. We have just plotted gt vs objects data but not compared or used the data to fit our needs. In order to find the lateral error we used these two graphs to plot the graph. Along the process we used linear interpolation to plot points in between points that could not be all measured to get a straight line graph. 







