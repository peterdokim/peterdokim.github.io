# Objection_detection_tool_GUI


## Project Outline


### Step 1. Understanding what the Project is about and making a powerpoint presentation 

Understanding the project took me some time as I was not really sure what I was doing from the start.
I knew that my learning came from making a GUI but what is it about GUI that I will be making? was really what I have been trying to ask
myself and my mentor for some time.

Making a powerpoint slide was also hard for me. 
#### I initially made this powerpoint.

![Screenshot from 2022-07-07 09-29-24](https://user-images.githubusercontent.com/61016872/177664285-a83dbb11-08da-418b-81f3-5673863577cf.png)
Obviously I got cut, wasn't what people wanted from me. Rather, I was planned to start from scratch refining my original document.

My second try resulted in this product,
![Screenshot from 2022-07-07 09-31-34](https://user-images.githubusercontent.com/61016872/177664531-dd17921a-248c-43bc-8f84-1997f283d0ec.png)
<br />
In my powerpoint, I had several outlines about the project.
  1. Project plan
  2. Project goal and object
  3. Project timeline and milestone
  4. Project outline and the details of the project
  5. Project outcome

**There are quite a lot of dependencies to install before you try anything. 
I learned it by trial and error, as my python file kept not running.
Install conda using pip install conda or any other method you find on computer
</br>Microsoft visual studio code is a great text editor when coding long codes, as it catches indentations and errors.**

### Step 2. Converting the jupyter file into python file, and making a tutorial GUI without any features.

[stackoverflow](https://stackoverflow.com/questions/37797709/convert-json-ipython-notebook-ipynb-to-py-file#:~:text=From%20the%20notebook%20menu%20you,py'%20option.)</br>
This stackoverflow page came in handy.
Command that were used was 
![Screenshot from 2022-07-13 17-10-08](https://user-images.githubusercontent.com/61016872/178684328-729700e9-2312-45d5-aecc-02895db97c07.png)

After converting to python file, I tried to make tutorial gui following code from the Internet and tutorials.</br>
Most common examples I followed were [Python으로 만드는 나만의 GUI 프로그램](https://wikidocs.net/book/2165).

The first base python files I made consisted of Mainwindow with hello world on it. I quickly learned different syntax within the python files, and integrated them to the workings. 

![Icon Page](https://user-images.githubusercontent.com/61016872/178687073-dcdc7113-79d6-4ba0-9bb2-f547b51697c1.png)

![Style page](https://user-images.githubusercontent.com/61016872/178687256-d565aa97-544d-4f68-8e89-3d927d5f461a.png)
</br>Later on I learned the different setstylesheet, qcombobox, setlayout, addwidget to maximize the user experience.

### Step 3. Implementing Actual GUI with PYQT5



#### SubStep 1. Making a MainWindow

![Screenshot from 2022-07-13 15-32-48](https://user-images.githubusercontent.com/61016872/178687654-02191605-8e3c-4ca3-8d6d-a746e60026d4.png)</br>
The MainWindow implementation was quite hard, as I kept learning how to make pushbutton. I searched on google several times to find the answers to making the MainWindow pushbuttons and the "create" button. I used if elif statements to press buttons for the right causes, and only some buttons to work when others do not work. Pressing the push button along with the create signals a new window to pop up which would be the graph plotter. 


#### SubStep 2. Making a graph plotter from the MainWindow
![Screenshot from 2022-07-13 15-37-32](https://user-images.githubusercontent.com/61016872/178689391-8e900f16-7efb-4a5a-9278-1b5e7b713e1e.png)</br>
Example of the graph plotting was quite hard, and I implemented material from someone who had previously written the code using qcombobox to change to different graphs. There are total of 9 plots in the process. For each GT vs KKP, GT vs MEYE, GT vs RT, there are 3 different plots. Speed quiver plot, Projection trajectory, Speed profile plots. These are implemented within the qcombobox.


![Screenshot from 2022-07-13 17-41-16](https://user-images.githubusercontent.com/61016872/178690412-11761c00-9647-4cec-adaf-b5efcffb7790.png)
What it looks like for different plots in the end.

### 아키텍쳐 구현 및 요구사항 분석




