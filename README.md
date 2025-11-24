THE PERFECT EGG TIMER



Project Overview:
THE PERFECT EGG TIMER is a command-line Python application designed to help users prepare eggs to their desired level of doneness. It functions as a virtual timer and guide, providing estimated cooking times and simulating the waiting process for different egg styles. The program starts with a large, stylized text display of its name and guides the user through selecting an egg type and quantity, then initiates a timed wait simulation.



Key Features:
Four Egg Styles: Users can select from four popular preparations:

Soft Boiled: Liquid yolk with soft whites (approx. 3-6 minutes).

Hard Boiled: Solid, slightly crumbly yolk with hard whites (approx. 12-15 minutes).

Fluffy Omelet: Golden cloud with tender, airy curds (approx. 8-10 minutes).

Sunny Side Up: A vibrant disc of liquid gold with crisp white (approx. 3-5 minutes).

Time Calculation: The program provides the estimated total cooking time and calculates the future time when the eggs should be removed, based on the current system time.

Visual Representation: Uses basic ASCII art to display an egg graphic before and after the simulated cooking time.

Quantity Input: Allows the user to specify the number of eggs (1-6).

Interactive Timer Simulation: Simulates the waiting process with a "Please wait..." output.



Technologies & Tools Used:
Language: Python 3

Libraries:

sys (for text output/flushing)

time (for delays/sleep functions)

datetime (for time calculation and display)



Steps to Install & Run the Project:
This is a single-file Python script, so installation is minimal.

1. Save the Script
Save the provided Python code into a file named THE PERFECT EGG TIMER.py on your local machine.

2. Open Terminal/Command Prompt
Navigate to the directory where you saved the file using your terminal or command prompt.

Bash

cd /path/to/your/project
3. Run the Script
Execute the file using the Python interpreter:

Bash

python "THE PERFECT EGG TIMER.py"
The program will start with an introductory text display and prompt you for input.



Instructions for Testing:
To test the application, follow these steps:

Start the program as described above.

Introduction Check: Verify that the large, stylized title text is displayed correctly.

Egg Selection: When prompted, enter a number from 1 to 4:

Enter 1 (soft boiled) and ensure the predicted time is 4 minutes and 30 seconds.

Enter 2 (hard boiled) and ensure the predicted time is 13 minutes and 30 seconds.

Enter 3 (fluffy omelet) and ensure the predicted time is 9 minutes and 0 seconds.

Enter 4 (sunny side up) and ensure the predicted time is 4 minutes and 0 seconds.

Quantity Check: When prompted, enter a number between 1 and 6. Verify that the initial ASCII egg graphic is displayed a corresponding number of times.

Timer Simulation: When prompted to start the timer, enter y, Y, yes, or YES.

Check that the Current Time and the Future Time are displayed correctly.

Observe the "STARTING THE TIMER NOW" message followed by the Please wait.... simulation. (Note: The actual wait time is simulated quickly using time.sleep(0.5) in the code for practical testing).

Completion Check: Verify that the "Your eggs are boiled/made, please take them out" message is displayed, followed by the final ASCII art for the selected egg type, displayed the number of times specified by the quantity.



Screenshots: 

<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/4c866549-52a7-493b-9628-30321c4aca75" />
<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/7efb08e4-adde-4c88-900c-3454d7a63589" />
<img width="1920" height="1080" alt="Screenshot (109)" src="https://github.com/user-attachments/assets/100a0d78-48ed-4851-b4ae-28af2a9dc528" />
<img width="1920" height="1080" alt="Screenshot (114)" src="https://github.com/user-attachments/assets/b30d9f48-517f-465c-abd1-4bae44ab1a27" />
<img width="1920" height="1080" alt="Screenshot (113)" src="https://github.com/user-attachments/assets/eb3f4979-ba8d-46c3-a814-d4e3b22f3eab" />
<img width="1920" height="1080" alt="Screenshot (112)" src="https://github.com/user-attachments/assets/32dac944-f488-4e6b-9bde-3da9ba16fb73" />
