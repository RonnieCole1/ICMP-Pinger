# ICMP-Pinger
An ICMP Pinger program that uses python socket programming.
How to compile and run the program:

Step 1: Make sure that Python 3 is installed. Also make sure that you are running the program as an administrator/superuser, otherwise you will be unable to run the program.

Step 2 (Optional): Put the ICMPPINGER.py file in your desktop.

Step 3: Open the command line. If you put ICMPPINGER.py in the desktop, type cd Desktop in the command line (otherwise, use the cd command to navigate to where the file is located.)

Step 4: To run the program, type python3 ICMPPINGER.py --target-host www.xavier.edu in the command line. You can use other URLs instead of www.xavier.edu in the command if you want to.

Step 5: The program will ping the target host 4 times, listing the time for the reply to reach your computer after each ping. If an error occurs, such as the packets timing out or attempting to run the program as a normal user, a corresponding error message will appear.
