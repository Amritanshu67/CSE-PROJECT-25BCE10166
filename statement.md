Statement:

Problem Statement:
The goal of cooking eggs to a specific doneness (e.g., soft-boiled, hard-boiled, etc.) is often undermined by inconsistent
timing and the lack of a simple, dedicated tool for precise calculation. Home cooks frequently end up with undercooked or 
overcooked results because they rely on variable methods or generic timers. This project addresses this by creating an 
interactive, console-based timer that automatically calculates and tracks the exact cooking time required for a user's 
chosen egg style and quantity, ensuring consistent and perfect results every time.



Scope of the Project:
The project is implemented as a Command-Line Interface (CLI) application using standard Python libraries.
    • Inclusions:
        ◦ Interactive Input: Prompting the user to select one of four predefined egg styles and the number of eggs (1-6).
        ◦ Precise Time Calculation: Using fixed time constants per egg style to determine the total cooking duration (minutes and seconds).
        ◦ Real-time Clock Integration: Calculating and displaying the exact future completion time based on the current system time.
        ◦ Simulated Timer: A simple, text-based progress indicator (using dots and time.sleep) to mimic a countdown.
        ◦ ASCII Art Display: Using large text and artistic representations (e.g., soft, hard, omelette, sunny) for engaging visual feedback.
    • Exclusions:
        ◦ Graphical User Interface (GUI).
        ◦ Advanced culinary factors (e.g., egg size, water temperature, altitude adjustment).
        ◦ Integration with external APIs, hardware, or networking.



Target Users:
The primary audience for THE PERFECT EGG TIMER is any user who prepares eggs and values consistency and simplicity.
    • Home Cooks: Individuals seeking a dedicated, reliable tool to perfect their technique for various egg types.
    • Students and Budget Cooks: Users who need a straightforward utility that requires no complex setup or external downloads.
    • Cooking Enthusiasts: Users who appreciate utility programs that incorporate interactive text and stylized console output.

    
    
High-Level Features:

Egg Style Selection	Allows the user to select from Soft Boiled, Hard Boiled, Fluffy Omelette, or Sunny Side Up via a numerical prompt.           
Quantity Management	Accepts an integer input for the number of eggs (1 to 6) and scales the cooking duration slightly based on this input (e.g., displaying the number of ASCII art eggs).                    
Duration Estimation	Provides the user with the pre-calculated time commitment in minutes and seconds before starting the timer.                 
Completion Time Predictor	Calculates and displays the Current Time and the precise Future Time when the eggs will be done using the datetime module.
Visual Timer Feedback	A line of dots (.) prints to the console at intervals to simulate the passage of time, engaging the user during the wait.                    
Stylized Output	Employs custom large-text ASCII art for the title screens and different stylized ASCII egg representations for the final output.
