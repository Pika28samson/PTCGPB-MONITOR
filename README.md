# PTCH Pocket Bot Monitor <br />
<br />
<em>For the actual bot, visit https://github.com/Arturo-1212/PTCGPB</em> <br />
<em>This program is used to monitor your bots on your phone even if you are not near your computer</em> <br />
<em>This program was made in a rush, so please dm me on discord if you have any issue: pika28samson</em> <br />
<br />

<strong>Step 1:</strong> <br />
Setup everything from artuto's bot. <br />
<br />
<strong>Step 2:</strong> <br />
Download <em>main.exe</em> and <em>ngrok.exe</em> from here.<br />
<br />
<strong>Step 3:</strong> <br />
Open <em>main.exe</em>, enter number of instances and the program should start.<br />
Firewall might pop up, choose <em>"Allow Access".</em> <br />
To access the page if you are in the same LAN as your computer, go to the website <em>http://[your computer's ip]:5000</em> <br />
e.g. <em>http://172.0.0.0:5000</em><br />
You can find your IP by going to <em>Command Prompt</em> and type <em>ipconfig</em> <br />
You should see something like  IPv4 Address. . . . . . . . . . . : 172.0.0.0<br />
<br />
<strong>Step 4 (Optional):</strong> <br />
If you want to access to the app even if you are not in the same LAN as your computer, do this step.<br />
Remember to also do the steps above.<br />
Sign up for Ngrok and copy the authtoken from dashboard: https://dashboard.ngrok.com/get-started/your-authtoken<br />
Open ngrok.exe and run this command: <em>ngrok authtoken &lt;your_authtoken_here&gt;</em> <br />
Once you've done these steps, you don't have to do it again.<br />
<br />
<strong>Step 5 (Optional):</strong> <br />
Every time you want to run the website, open ngrok.exe and type this command: <em>ngrok http 5000</em> <br />
You should see something like this:<br />
Forwarding                    http://abcd.172.0.0.0.ngrok.io -> http://localhost:5000<br />
Now you have done everything! Just go to the website shown above!<br />
e.g. http://abcd.172.0.0.0.ngrok.io<br />
<br />
<strong>Good Luck Everyone!</strong>
