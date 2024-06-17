# CSA0874-python-programminng
DESKTOP NOTIFICATION TO DRINK WATER USING PYTHON:
The purpose of this article is to develop a notification system that reminds users to drink water at fixed intervals. 
The program described below first prompts the user to input a time interval for the notifications.
It then repeatedly sends reminders to the user to drink water until the user stops the script. Additionally, after each interval, the program creates a text file to log the times when the user drank water.
**MODULES USED:**
**time**: To manage the interval time.
**win10Toast** : To send quick notification.
**datetime** : To keep record of time and date in log.

**STEPS INVOLVED:**
Import the necessary module.
Prompt the user to input the time interval, asking for hours, minutes, and seconds.
Convert the input time into seconds and return this value to the main function.
Implement a loop to start the timer and generate a toast message when the timer reaches the set interval.
After sending the notification, call a function to write a log file. This function will capture the current date and time.
Create a .txt file and append the drink water log to it.
