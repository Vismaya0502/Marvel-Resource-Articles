# **Level 0 Report**
---
# Task 2: API

#### The task was to understand the concept of APIs and to learn their practical implementation.

- APIs act as a mediator between two systems or applications.
- They enable communication and data exchange between different services.
---
- For the Implementation of API, I used two different APIs to build two different applications.
- I used Spotify's API to get the data of my music lisetning history.
- and built a call app using an API to generate a number and through which i could make calls to specified numbers.
- --

![api](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/api.jpeg?raw=true)
---


---
# Task 3: Working with Github

The task was to understand how GitHub works, explore its basic actions, and apply them by performing tasks in a given repository.

- Learned that GitHub allows collaboration and easy access to project files.
- Explored key features like issues, pull requests, and repositories.
- --
- Forked the given repository and followed the README instructions.
- Found and fixed an error in the addition code (Removed an extra +1).
- Committed the change and created a pull request to submit the fix.
- ---

# Task 4 : Get familiar with the command line on ubuntu

The task was to practice basic Linux commands on Ubuntu and become familiar with using the command line interface in Linux OS.

- Learned commonly used Linux commands such as cd, ls, and touch etc
- Understood how these commands make navigation from one directory to another easy and file handling more time-efficient compared to manual methods.
- ---
- Created a directory using **mkdir** command and navigated to it using the **cd** command.
- Used the **touch** command to create blank files.
- Listed all files in the directory with the **ls** command.
- Created 2600 folder using single command.
- Created two text files and added some random text to them and concantenated both the files and displayed their content on the terminal using cat command.

---

![ubuntu1](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Ubuntu2.jpeg?raw=true)

![ubuntu](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Ubuntu1.jpeg?raw=true)

---



# Task 5 : Linear Regression from Scratch

The task was to learn the concept of linear regression, understand the mathematics behind it, and learn how gradient descent is used to optimize the model

- Studied the fundamentals of linear regression and the mathematics of linear regression.
- Understood how gradient descent is applied to minimize error and improve the regression model.
- Understood the role of the learning rate in controlling convergence between actual model and scratch model.
- Realized the importance of choosing an proper learning rate for efficieny of the model.
- ---
- Coded linear regression from scratch.
- Then applied gradient descent to optimize the model parameters such as slope and intercept.
- Experimented with different learning rates to see their effect on model performance.
- Compared the scratch implementation with an existing library based model to understand the results and then use suitable learning rates.

[Linear Regression Jupyter Notebook](http://localhost:8888/lab/tree/Linear%20regression%20from%20scratch.ipynb)

![lr](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/LinearRegression.jpeg?raw=true)
- ---

# Task 6 : The Matrix Puzzle
- I learned both NumPy and Matplotlib fundamentals
- In NumPy, I learned how to add elements to an array, access elements, resize arrays, slicing, reshaping, and other operations.
- In Matplotlib, I learned how to plot different kinds of graphs, and also understood that different types of data are better visualized using different types of graphs.
- I understood that NumPy makes working with matrices much easier and faster.
- NumPy also stores data in a much more convenient way compared to normal Python lists.
- ---
- I first loaded the scrambled matrix and tried visualizing it to see how it looked.
- Then I checked the array dimensions and saw there were 10,000 elements(i.e. 200 x 50 = 10,000).
- That made me realize the picture might be square, hence tried to reshape into 100 × 100 (since 100 × 100 = 10,000).
- After reshaping, I tried rotating and flipping the array to fix its orientation.
- And, I got the correct image after rotating.

---
![NumPy](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Numpy3.jpeg?raw=true)

![Numpy](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/NumPy1.jpeg?raw=true)
  
---
# Task 7 : Portfolio Webpage

The task was to create a webpage using HTML and or any other frameworks

- Created my portfolio webpage using HTML and CSS
- Included sections like about me, education, projects etc.
  
----
![webpage](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Screenshot_12-9-2025_221645_127.0.0.1.jpeg?raw=true)

  Link to GitHub repo : [Click here](https://github.com/Vismaya0502/Portfolio)
- ---

# Task 8 : Markdown

The task was to write a resource article on any topic of my choice using Markdown to learn the Markdown syntax and understand how to structure content in a clean and readable format.

- Learnt how to write in Markdown.
- Learned the syntax for formatting text, such as making words bold, italic, create headings, bullet points, and horizontal lines(Double Asterisk for **Bold** or ctrl+ B , Single asterisk for *Italics* or ctrl+ I)
- ---
- Chose a topic (FFT in Music) and wrote a resource article using Markdown syntax.
- Uploaded the article to GitHub and hosted it for easy access.

[FFT](https://github.com/Vismaya0502/Marvel-Resource-Articles/blob/main/FFTM.md)

# Task 9 : Tinkercad

The task was to learn how to build and simulate electronic, arduino circuits using tinkercad

- Tinkercad provides a very convenient way to simulate microcontroller based circuits and test them before assembling the actual circuit.
- This makes easier to experiment with components.
- ---
- Studied and understood the example circuits provided in Tinkercad.
- Simulated a simple circuit using an ultrasonic sensor to measure the distance between the sensor and an obstacle/object.
- ---
![Tinkercad](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Tinkercad.jpeg.jpeg?raw=true)
- ---
# Task 10 : Speed Control of DC Motor

The task was to learn how to control the speed and direction of a dc motor using L298N Motor driver.

- L298N is a motor driver, which is capable of controlling both speed and direction of motors.
- To control the speed of the motor it uses PWM signal, while the direction is controlled by H-bridge circuit.
- It has got two H-bridge circuits, hence it can support two motors at a time.
- ---
- Assembled the circuit using the L298N motor driver and a DC motor and an Arduino.
- Connected the motor driver to control both the speed (PWM) and direction (H-bridge).
- Tested the circuit and successfully observed the motor’s speed variation(i.e Motor rotates when the signal is high, stops when signal is low) and change in the direction of rotation.
- A video of the same is included below :

   [Click here](https://youtube.com/shorts/KUeTf6jgI_Q?feature=shared)

- ---
# Task 11 : LED Toggle using ESP32

The task was to learn the working of ESP32 by controling the toggling of LEDs using ESP32

- I understood that ESP32 is a much better microcontroller compared to Arduino because it has built-in Wi-Fi and Bluetooth support.
- Which makes it great for IoT projects since we can directly connect devices it to internet.
- I also understood that ESP32 can be programmed in similar to Arduino using the Arduino IDE itself.
---
- Referred to the given online resource that explained how to build a circuit for LED toggling using ESP32.
- Built the circuit with two LEDs connected to ESP32.
- Connected with ESP32 Wi-Fi and opened a web server.
- The web server displayed two options for LED1 and LED2. By clicking on these, I could toggle the LEDs on and off.
- ---
![ESP32](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/ESP321.jpeg.jpeg?raw=true)
---

### Challenges Faced:

- I faced difficulty in understanding the Wi-Fi configuration part of ESP32.
- The circuit didn’t work when resistors were connected in series with the LEDs. But when I removed the resistors, the LEDs started working properly.

# Task 12 : Soldering Prerequisites

The task was to learn how to solder electronic components. For this, I practiced soldering by attaching a piece of soldering wire to an electronic component on the PCB.

---
![Soldering](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Solder.Jpeg.jpeg?raw=true)
---


# Task 13 : Astable Multivibrator using 555 timer

The task was to design a 555 astable multivibrator with a duty cycle of 60%, rig up the circuit on a breadboard, and observe the output waveform on a oscilloscope.

-Understood that multivibrators are circuits used to generate waveforms and are used to control timing functions.
- Learned the working of an astable multivibrator using the 555 timer IC, including how resistors and capacitors decide the duty cycle. 
- Simulated the circuit in LTSpice to verify the design before implementing it physically.

---
- Constructed the circuit on a breadboard using a 555 timer, resistors, and a capacitors.
- Observed the waveform on the Oscilloscope and verified that the duty cycle was around 58%.

![Astable MV](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/AstableMV.JPEG.jpeg?raw=true)

![Astable MV](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/AstableMV1.jpeg.jpeg?raw=true)


---
# Task 14 : K-Maps

The task was to learn about Karnaugh Maps (K-maps) and use them to implement a burglar alarm circuit.

- Understood that K-maps are used to simplify Boolean expressions and design optimized logic circuits.
- Learned how different input conditions (such as door open/closed and lock status) can be represented in truth tables and then reduced using K-maps.

---

- Created a truth table for four conditions of the burglar alarm (based on whether the door was locked/unlocked and opened/closed).
- Derived the simplified logic expression using a K-map.
- Designed and tested the circuit in Tinkercad and also verified it in a digital circuit simulator.
- --

![K-Map](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/WhatsApp%20Image%202025-09-11%20at%2023.17.38.jpeg?raw=true)

|

![K-map](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/WhatsApp%20Image%202025-09-11%20at%2023.19.46.jpeg?raw=true)

![K-maps](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Kmap1.jpeg?raw=true)

---
# Task 16 : Datasheet Report Writing

The task was to study the datasheet of the L293D motor driver, understand its specifications and pin configurations and write a report on it.

[Datasheet report](https://github.com/Vismaya0502/Marvel-Resource-Articles/blob/main/Datasheet.md)
----
# Task 17 : Introduction to VR

The Task was to study about VR and differentiate it from AR and study the current trends and technologies in the VR space.

The report has been uploaded to GitHub for reference.

[VR](https://github.com/Vismaya0502/Marvel-Resource-Articles/blob/main/VR.md)
---

# Task 18 : Sad Servers

In this task, we had to use Linux commands to solve puzzle-like scenarios, and finally had reach the solution to make the Sad servers happy.

- Learned that Linux commands go beyond basic operations and can be applied for troubleshooting as well.
- Used commands like ls, cd, cat, grep, and echo to solve the puzzle.

----
- Step by step, solved the Command-Line Murders by using the Linux commands.

- Used commands such as:

    - ls → to list files and folders inside a directory

  - cd → to navigate between directories

   - cat → to read file contents and concantenate them

   - grep → to search patterns in files

  - echo → to print output and final results

Successfully reached the final answer, hence completing the scenario and making the Sad server happy.

![Sad_Server](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/SadServers.jpeg.jpeg?raw=true)
---
# Task 19 : Web-App

The task was to create a simple web app. I built a To-Do tasks app where I can add tasks and manage them.

- Included a task list where tasks can be added.
- Added swipe functionality (right = done, left = skip).
  
[Github Repo](https://github.com/Vismaya0502/web_app_Slide_to-do)

![app](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/Screenshot_12-9-2025_232043_127.0.0.1.jpeg?raw=true)


# Task 20 : Jupyter Notebook

The task was to get familiar with Jupyter Notebook and understand how it can be used both for coding and for creating reports.

- Understood that it can be used both for coding (code cells) and for writing reports (Markdown cells).
- Learned basic Markdown features like adding titles, bullet points, bold/italic text, lins, and inserting images.


---
- Opened a new notebook and wrote a short Markdown report.
- Tried out Markdown formatting.
- Added some Python code and plotted a simple graph.

[Jupyter Notebook](http://localhost:8888/lab/tree/jupyternb.ipynb)

![jypnb](https://github.com/Vismaya0502/Marvel-Report-Images-2/blob/main/jupyternb.jpg.jpeg?raw=true)
---

# Task 21 : Intro to Machine Learning

THe task was to watch two videos explaining about the machine learning and how to prepare data and write a resource article summarizing both the videos.

[machine_learning.md](https://github.com/Vismaya0502/Marvel-Resource-Articles/blob/main/ml.md)





























