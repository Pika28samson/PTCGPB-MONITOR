# PTCH Pocket Bot Monitor

*For the actual bot, visit https://github.com/Arturo-1212/PTCGPB*
*This program is used to monitor your bots on your phone even if you are not near your computer*
*This program was made in a rush, so please dm me on discord if you have any issue: pika28samson*

**Step 1:**
\nSetup everything from artuto's bot.

**Step 2:**
Download *main.exe* and *ngrok.exe* from here.

**Step 3:**
Open *main.exe*, enter number of instances and the program should start.
Firewall might pop up, choose *"Allow Access".*
To access the page if you are in the same LAN as your computer, go to the website *http://[your computer's ip]:5000*
e.g. *http://172.0.0.0:5000*
You can find your IP by going to *Command Prompt* and type *ipconfig*.
You should see something like  IPv4 Address. . . . . . . . . . . : 172.0.0.0

**Step 4 (Optional):**
If you want to access to the app even if you are not in the same LAN as your computer, do this step.
Remember to also do the steps above.
Sign up for Ngrok and copy the authtoken from dashbaord: https://dashboard.ngrok.com/get-started/your-authtoken
Open ngrok.exe and run this command: *ngrok authtoken <your_authtoken_here>*
Once you've done these steps, you don't have to do it again.

**Step 5 (Optional):**
Every time you want to run the website, open ngrok.exe and type this command:
*ngrok http 5000*
You should see something like this:
Forwarding                    http://abcd.172.0.0.0.ngrok.io -> http://localhost:5000
Now you have done everything! Just go to the website shown above!
e.g. http://abcd.172.0.0.0.ngrok.io

# Good Luck Everyone!
