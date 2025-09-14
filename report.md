# TASK 1: TINKERCAD

**Objective:** The objective of this task was to create a tinkercad account & to make a simple circuit to estimate the distance between the ultrasonic sensor and the object.

**Components and Connections:**    
Below is the list of components used for the task:

![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/7985cb49e85f0b52039d700fca0faea9f276811e/Screenshot%202025-09-11%20143336.png
)

Connections :  
**a)Ultrasonic Sensor -	Arduino UNO**  
              VCC --> 5V  
TRIG -->	    Pin 8\
ECHO -->	Pin 9   
GND -->	GND   
**b)LCD (16x2) 12C	- Arduino UNO**  
VCC -->	5v  
SDA -->	Blank pin\
SCL -->	Blank pin\

GND --> GND  
**c)Servo Motor -	Arduino UNO**\
Ground -->	GND\
Power -->	5V\
Signal -->	Pin 3\
below image is the circuit made in the tinkercad:\
![image](https://github.com/Thanu-cpu/Marvel-level-0-report/blob/main/Screenshot%202025-08-24%20202651.png?raw=true)\
**Learnings and outcomes:**\
Familiarized with Arduino boards, including analog and digital pins, and the working of ultrasonic sensors. Ultrasonic refers to frequencies higher than 20 kHz, which are inaudible to humans. There are two parts to an ultrasonic sensor: a transmitter, which sends ultrasonic  waves, and a receiver, which receives the reflected waves from an object. This allows the distance to be calculated using the speed of the  waves emitted by the sensor and the time required for the receiver to detect the reflected waves, based on the formula.\
 d = s × t\
![image](https://github.com/Thanu-cpu/Marvel-level-0-report/blob/main/Screenshot%202025-09-11%20160549.png?raw=true)\
[click here](https://www.tinkercad.com/things/2w9rKFhDLur-frantic-fulffy-snicket/editel?returnTo=%2Fdashboard%2Fdesigns%2Fcircuits) to view my circuit.
# TASK 2: API
**Objective:** Learn the working of an API and its applications. Using any API of your choice, build a user interface (web app, mobile app, etc), where you can make calls and then display the necessary information.\
**Learnings and outcomes:** Developed a weather app that displays the weather for any location. To start, I obtained an API ID from OpenWeather API and then used HTML to build the web app.
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/4282b80aa3db6a65ea103a65e48e82e4b202f692/Screenshot%202025-09-11%20172324.png)\
[click here](https://youtu.be/ilSoEzVwAFE?si=SZvauDDlTioIRXV-) to view my app working.
# TASK 3: WORKING WITH GITHUB
**Objective:** Familiarize yourself with GitHub integrated workflows (GitHub actions), Issues, and pull requests with this task. Given below is a git repository, go check it out and then perform the necessary tasks stated in the readme file as given in the MARVEL website.\
**Learnings and outcomes:**\
1)Firstly,i created my github account.\
2)Learned how to create and delete repository.\
3)Familiarize with github environment and learned how to fork and clone the repository, branch creation.\
4)I forked the given repository into my repository and then cloned the repository, in order to complete the given specified marvel task.\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/7b605c0f4b875d6935c12b1ef4e31e0e85d34324/Screenshot%202025-09-11%20173803.png)

# TASK 4: COMMAND LINE ON UBUNTU
**Objective:** Get familiar with the command line on ubuntu.\
**Learnings and outcomes:** I learned basic Linux commands like,
1) 'mkdir' to create folders.
2) 'cd' to navigate directories.
3)   'touch' to create blank files.
4)    'ls' to list files.
5)  create multiple folders efficiently using loops.
6)  'cat' to concatenate text files.\
   Using these basic commands, I completed the subtasks.\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/e10e7e15fd2a17a6b208435e4ccc7b25725fc0f5/Screenshot%20from%202025-09-03%2016-45-12.png)
 # TASK 5: PORTFOLIO WEBPAGE
 **Objective:** Create a website to showcase your portfolio - about yourself, interests, projects, social media profiles and more. It has to be responsive and also pushed to the git repository. CSS can be of your choice and any framework can be used.\
 **Learnings and outcomes:** I created my first portfolio,which showcasing my interests, skills, projects, and contact details using HTML and CSS. I pushed it to a Git repository, making it accessible to everyone and gained valuable knowledge about web development and the basics of HTML and CSS.\
[click here](https://github.com/Thanu-cpu/thanujagr-.marvel.io.git) to view github repository.\
[click here](https://thanu-cpu.github.io/thanujagr-.marvel.io/) to view my portfolio.
# TASK 6: SPEED CONTROL OF DC MOTOR
**Objective:** Understand the control DC motors using the L298N motor driver and the Arduino board. Using an UNO and H-Bridge L298N motor driver, control the speed of a 5V motor.\
**Components and Connections:**\
Below is the list of components used for the task:\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/c6ac9fcf119cbe6a43049c236352f0195c9a26ec/Screenshot%202025-09-11%20204432.png)\
I reffered the below circuit for connections:\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/59275bddc8d5c768e2d8e6ff08398369d8da42d7/Screenshot%202025-09-11%20210919.png)\
**Learnings and outcomes:** 
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/b28e675ae918dc5922f3b2f45b0e58e436e88b0b/Screenshot%202025-09-11%20221815.png)\
L298N motor driver can control speed and direction of 2 motors at a time independently.In this task only 1 motor is used to demonstrate.\
1)Based on H bridge principle.\
2)4 input pins(IN1,IN2,IN3,IN4) ,since we took 1 motor so IN1 & IN2 pins are used for connection.It has two input pins (IN1, IN2) to set the motor’s rotation direction.\
3)An enable pin (ENA) to control speed through PWM signals from a microcontroller like Arduino.\
4)By adjusting the PWM duty cycle on ENA, the motor’s speed can be varied.\
5)The higher the duty cycle, the higher the average voltage applied to the DC motor, resulting in an increase in motor speed. The shorter the duty cycle, the lower the average voltage applied to the DC motor, resulting in a decrease in motor speed.\
Here is the image of  performing this task:\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/a462e512cd649e214deb4ebb5e857ddd8174e3eb/WhatsApp%20Image%202025-09-11%20at%2010.45.56%20PM.jpeg)
[click here](https://youtu.be/WFRDR2sopUM) to view the video of performing task.
# TASK 7: LED TOGGLE USING ESP32
**Objective:** Learn the working of an ESP32 and create a standalone web server with an ESP32 that controls the LED connected with ESP32 GPIOs. Use the arduino IDE to code and upload the program to the ESP32. Learn to configure the IDE to upload code to an ESP32.\
**Components and connections:**\
Below is the list of components used for the task:\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/6610309424b79752dd6abed7d9b2312607f30dab/Screenshot%202025-09-11%20230710.png)\
Connections:\
Referred below circuit along with the marvel website resource for the connections.\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/ee9b2fcab089111a1811f549e9c00116d79eb3a8/Screenshot%202025-09-11%20230748.png)\
**Learnings and outcomes:**\
Familiarized with ESP32 microcontroller.\
Feeded the code to microcontroller through Arduino IDE.After the succesful compilation,i received the IP address,pasted the address to browser & toggled the LED using same website.
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/f3ea4170675ad83738d1b24a6fc22c9dde760fe3/WhatsApp%20Image%202025-09-11%20at%2011.32.24%20PM.jpeg)
[click here](https://youtu.be/UEmksmfeWGM) to view the video of LED Toggle.
# TASK 8: K-MAP & DERIVING LOGIC GATES
**Objective:** Determine the Karnaugh map and make a burglar alarm using simple logic circuits. The buzzer or led blinks when certain conditions are met, you can use push buttons for the door and key.\
**Learnings and outcomes:**\
The task is to build a security alarm that alerts the user in case of unauthorized access, i.e., when the door opens in the absence of the key. Using CircuitVerse software, I built a circuit using an AND gate and a NOT gate along with an LED. Assumptions: Let's denote,
1) Door by 'D', where an open door is represented by 1 and a closed door by 0.
 2) Key by 'K', where key insertion is represented by 1 and absence by 0.\
  Below is the truth table reffered to build the alarm,\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/3a9a6293e9c40d661361414f43806a435be4bc27/Screenshot%202025-09-13%20112159.png)\
  K-map of the above truth table and the logic circuit followed,\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/5684f9705da7cc8c3bd8f64b0b1661bc88518ed1/Screenshot%202025-09-13%20113135.png)
  3)Output is denoted by 1.\
  When output is 1,LED will turn on.\
  Below is the logic circuit i built for security alarm,\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/dd0ead4c2a4592e0318e8c2677d390761e20d727/Screenshot%202025-09-09%20210731.png)\
  [click here](https://youtu.be/aDG2m28McBU) to view the working of security alarm circuit.
  # TASK 9: SOLDERING PREREQUISITES 
  **Objectives:**  Learn about the soldering equipment and perform basic soldering on a perf board, for example a LED circuit.\
  **Learnings and outcomes:** \
  familiarized with soldering equipment like the solder, the soldering iron, soldering wick, flux etc.Also learned the technique of soldering and desoldering.\
  below is the image of soldering done in the lab by me:\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/6df8b48f91f3172c8e78babc7fcfe71c66667a50/WhatsApp%20Image%202025-09-13%20at%2012.45.56%20PM.jpeg)
  # TASK 10: 555 ASTABLE MULTIVIBRATOR
  **Objective:** Design a 555 IC astable multivibrator with 60% duty cycle.\
  **Components and Connections:**\
  Components required:\
  1)555 IC Timer.\
  2)2 Capacitor (102)- 0.1nF.\
  3)2 Resistor-> R1-10k ohm & R2-20k ohm.\
  Connections:\
  referred above circuit diagram for the connection:\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/0543d9aaa979ee0df489cbbf18cbb0a533ca8970/WhatsApp%20Image%202025-09-13%20at%202.27.33%20PM.jpeg)\
  **Learnings and outcomes:** \
  Familiarized with the pins of 555 IC timer,internal structure of the IC and types of multivibrator.Learned the working technique of timer,SR flip flop with truth table and it's applications.\
  On the basis of charging and discharging of capacitor, i get the knowledge about astable multivibrator.\
  image of 555IC with pin labelled,SR flipflop truthtable and internal circuit of the IC:\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/2cc935b98d446736aa8b455b006cddd57b5a170f/Screenshot%202025-09-13%20162937.png)\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/e1dc0ce9bf4c85c82239002917b32ffe016099dd/Screenshot%202025-09-13%20154226.png)\
  Here,the specified duty cycle is 60%.While conducting this task i got 59.21% of duty cycle.The formula of duty cycle is,\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/8aab72742c441cbdd6315da130994d879e3f5891/Screenshot%202025-09-13%20164300.png)\
  Glimpse of performing the task:\
  ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/085e4cf4af0e307867fc02c1c304cadcc943f950/WhatsApp%20Image%202025-09-11%20at%2010.48.48%20PM.jpeg)\
  [click here](https://youtu.be/-FcHUdAt2VU) to view the complete task.
  # TASK 11: 3D PRINTING
  **Objective:** Understand the working of a 3D printer, check out the online resources. Understand what's an STL file, and then learn to slice it. Learn about bed temperature, and other printer settings. Finally get an STL file from the internet, and slice it and put it for print.\
  **Learnings and outcomes:**\
  1)​Nozzle Temperature:
For most PLA filaments, the ideal nozzle temperature is between 190°C and 220°C. Starting at 200°C is a good baseline, but you can adjust based on the specific brand and color for the best results.

2)​Bed Temperature:
While PLA can be printed on an unheated bed, using a heated bed set between 50°C and 60°C is highly recommended to improve first-layer adhesion and prevent the corners of your print from lifting (warping).

3)Printing Speed:
A standard printing speed of 40-60 mm/s provides a great balance between print time and quality. For outer walls or highly detailed sections, slowing down to 20-30 mm/s can significantly improve the surface finish.

​4)Cooling Fan:
After the first one or two layers, your part cooling fan should be running at 100%. Proper cooling is essential for PLA to harden quickly, which allows for sharp details, clean bridges, and steep overhangs.

5)​First Layer Settings:
To ensure a successful print, make the first layer slightly slower and thicker than the rest. A common practice is to set the first layer speed to 20 mm/s and the layer height to 0.3 mm for excellent bed adhesion.

6)​Post-Printing Procedures:
Once your print is complete, parts can be finished in several ways. PLA can be easily sanded for a smooth surface, primed and painted with acrylics, or joined together using cyanoacrylate (superglue) or a two-part epoxy.\
NOTE: Due to some issue in 3D printer i wounldn't able to print the model.I'll print the model as soon as issue is fixed.
# TASK 12: ACTIVE PARTICIPATION 
**Objective:** Take part in any technical event, inter or intra college and submit the issued certificate of participation.\
**Outcome:**\
I participated in two events:
1. KAGADA's poster track on mental health, where our team created and presented a poster.
2. CodeFury, where our team choose the agricultural theme. We started building a web  to connect markets and farmers for fair prices, but due to time constraints partially completed the backend development, while the frontend development was fully done.\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/e1c6729a64014e7ecbd7c60ce3daa197c9b94ed3/Screenshot%202025-09-13%20175915.png)\
![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/c4a90fa5ee91d7d200dec4900b675229934d87c1/Screenshot%202025-09-13%20180316.png)
# TASK 13: INTRODUCTION TO VR
**Objective:** Familiarise yourself with what Virtual Reality is. Make a detailed study about what's the difference between VR and AR.\
**Learnings and outcomes:** 

 **VIRTUAL REALITY (VR):**
 It is the term used to describe a three dimentional,computer generated environment that can be explored and interacted with.

 **AUGMENTED REAITY (AR)**:
 It is an interactive experience that enhances the real world with computer generated perceptual information.

 **DIFFERENCE BETWEEN VR AND AR**:
|VR           |AR        |
|:------------|:--------|
| VR completely replaces what people see and experiance|AR adds to the real world scene.|
|In a virtual reaity experiance,users are fully immersed|It is open and only partialy immersed|
|Enabed through VR headsets such as Google Daydream,Oculus Go etc|Enabled through devices such as AR glasses,smart lenses etc|
|VR samples: Smallworlds and Second life.|AR samples: Snapchat lenses,IKEA's place.|\

 **INDIAN COMPANIES AT VR AND AR**
 There are many companies are developing VR and AR:
 ### Imaginate :
 It started as an AR ,VR,MR company. That provided custom made 3D content for immersive training and support for various equipment and processes.
 ### Paralax Labs :
 It is a Mumbai-based startup for the defence and enterprise sectors.
 ### Tata ELXSI and many other companies.
 Using VR , i played some games.
 [click here](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/8506df2b7d5a21cab84dedb156e0e94f1cc1e43e/WhatsApp%20Image%202025-09-13%20at%2012.45.07%20PM.jpeg) to see.
 # TASK 14: THE MATRIX PUZZLE
 **Objective:** Get hands-on with NumPy and Matplotlib by solving a visual puzzle. You’ll be given a scrambled matrix, and your mission is to decode it into a hidden image using NumPy operations and visualization techniques.\
 **Learnings and outcomes:**\
 Familiarized with numpy operations like reshaping,slicing,transposing,and flipping arrays to decode a jumbled matrix into a hidden image ,this task gave me practical experience with numpy.Additionally,I learned how to use Matplotlib's imshow() function to visualize data,making sure that the dimensions and orientation are correct for a clear display.This exercise improved my knowledge about data manipulation and numerical computing concepts. All things considered ,it improved my capacity to use python libraries for practical applications such as data visualization and image processing.\
 Here is the decoded hidden image:\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/0724f7fc1d4e18beb4c2b6213ee516357cc0f56b/Screenshot%202025-09-14%20111754.png)\
 [click here](https://github.com/Thanu-cpu/thanujagr-.marvel.io/blob/aba1868433e9ee868c101a1d6f6c866d65746429/decoded.py) to view the code i used for decoding.
 # TASK 15: LINEAR REGRESSION FROM SCRATCH
 **Objective:** Dive into the core of machine learning by implementing Linear Regression from scratch using , and compare its performance with the scikit-learn implementation. Use the California Housing dataset to evaluate your model on real-world data.\
 **Learnings and outcomes:** \
 Linear Regression is a machine learning algorithm used to predict continuous values based on given input data. It assumes a linear relationship between the dependent variable (output) and independent variables (inputs). The equation for a simple linear regression is:\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/ee3ce4a604e3ae723d7ce61af6ea3efca85aaa53/Screenshot%202025-09-14%20232729.png)\
 Where ,y is the predicted value,m is the slope(weight in linear regreesion),x is the input values.\
 Linear regression is commonly used in predicting house prices, sales forecasting, and risk analysis.\
 **To measure how well the model is performing, error metrics are used.**  The Mean Squared Error (MSE) calculates the average of the squared differences between actual and predicted values:\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/e589f8422c4d0e4ab478d3834a567e7e93575dcf/Screenshot%202025-09-14%20232738.png)\
 Similarly, the Mean Absolute Error (MAE) calculates the average of the absolute differences:\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/b832a59c44c290cc339f715b92587a906b5d54b9/Screenshot%202025-09-14%20232745.png)\
 Here yi is the actual value ,other one is predicted value and n is the total number of data points.\
 To make the model accurate,gradient descent is used to minimize the error by adjusting the slope(weight) and intercept.formula for gradient descent is,\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/6d9f9be4acf8a0cec9c231c5de6ee81967b39014/Screenshot%202025-09-14%20232752.png)\
 Where,alpha is the learning rate controls the step size. By continuously updating these values, the model finds the line of best fit, which gives the most accurate predictions.
 # **DOMAIN SPECIFIC TASKS** 
 # TASK 16: NOTEBOOK NINJA-GETTING STARTED WITH JYPYTER
 **Objective:** Familiarize yourself with Jupyter Notebook as a tool for both coding and communication.This task is designed to build confidence in writing clean, readable, and well-structured notebooks using both code and Markdown.\
 **Learnings and outcomes:**\
 a)I gained knowledge about Jupyter Notebook and created my first notebook.\
 b)I learned how to install and use Jupyter Notebook, writing well-structured notebooks by combining code cells for execution and Markdown cells for clear documentation.\
 c)This improved my skills in writing clean and organized notebooks.\
 d) I gained confidence in organizing projects professionally, a crucial skill in fields like data science and AI.\
 e)Familiarized with jupyter notebook environment and learned some basic of python,and basic functions of matplotlib python library.\
 Here is the image of notebook i have created:\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/7f650ccab732a115db8116c7fa2ab075602582af/Screenshot%202025-09-14%20100641.png)\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/0e250045f015cd8df199815082368f83b791c118/Screenshot%202025-09-14%20100827.png)\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/c3b5ccbef79d2ba39593734510c8b50c42a4eb2c/Screenshot%202025-09-14%20100902.png)\
 ![image](https://raw.githubusercontent.com/Thanu-cpu/Marvel-level-0-report/aab64fe0f4f03db28ea6ddcb481661896c185dd9/Screenshot%202025-09-14%20100922.png)\
 [click here](https://github.com/Thanu-cpu/jupyter-notebook/blob/2264d707df3ca99c6d52239ff6bd75e76fabdf0c/jupyter_task.ipynb) to view the notebook!.
 # TASK 17: INTRODUCTION TO MACHINE LEARNING
 **Objective:** Understand foundational ML concepts and data preparation techniques by watching two beginner-friendly videos and writing an article.\
 **Learnings and outcomes:** The task is to watch the video mentioned and understand the concept and write a article on it.\
 [click here](https://github.com/Thanu-cpu/thanujagr-.marvel.io/blob/5d09595c725b9c6a2c092339f893a10da2fe05fd/ML.md) to read the article.



​



   




















