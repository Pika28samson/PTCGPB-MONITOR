# PTCH Pocket Bot Monitor <br />
<br />
*For the actual bot, visit https://github.com/Arturo-1212/PTCGPB* <br />
*This program is used to monitor your bots on your phone even if you are not near your computer* <br />
*This program was made in a rush, so please dm me on discord if you have any issue: pika28samson* <br />
<br />
**Step 1:** <br />
Setup everything from artuto's bot. <br />
<br />
**Step 2:** <br />
Download *main.exe* and *ngrok.exe* from here.<br />
<br />
**Step 3:** <br />
Open *main.exe*, enter number of instances and the program should start.<br />
Firewall might pop up, choose *"Allow Access".* <br />
To access the page if you are in the same LAN as your computer, go to the website *http://[your computer's ip]:5000* <br />
e.g. *http://172.0.0.0:5000*<br />
You can find your IP by going to *Command Prompt* and type *ipconfig* <br />
You should see something like  IPv4 Address. . . . . . . . . . . : 172.0.0.0<br />
<br />
**Step 4 (Optional):** <br />
If you want to access to the app even if you are not in the same LAN as your computer, do this step.<br />
Remember to also do the steps above.<br />
Sign up for Ngrok and copy the authtoken from dashbaord: https://dashboard.ngrok.com/get-started/your-authtoken<br />
Open ngrok.exe and run this command: *ngrok authtoken <your_authtoken_here>* <br />
Once you've done these steps, you don't have to do it again.<br />
<br />
**Step 5 (Optional):** <br />
Every time you want to run the website, open ngrok.exe and type this command: *ngrok http 5000* <br />
You should see something like this:<br />
Forwarding                    http://abcd.172.0.0.0.ngrok.io -> http://localhost:5000<br />
Now you have done everything! Just go to the website shown above!<br />
e.g. http://abcd.172.0.0.0.ngrok.io<br />
<br />
# Good Luck Everyone!
