# Onload-loccation
This code uses the navigator.geolocation.getCurrentPosition() function to obtain the user's location. If the user denies permission to access their location, the showError() function is called to display an appropriate error message. If the user grants permission, the showPosition() function is called to send the location data to Telegram.

Install PageKite on Kali Linux by running the following command in the terminal:
arduino
Copy code
sudo apt-get install pagekite
Once the installation is complete, create a PageKite account on their website at https://pagekite.net/ and obtain an authentication token.

In the terminal, enter the following command to start PageKite:

css
Copy code
pagekite.py --start --frontend=YOURNAME.pagekite.me:80 YOURTOKEN localhost:YOURPORT
Replace "YOURNAME" with your desired PageKite subdomain, "YOURTOKEN" with your authentication token, and "YOURPORT" with the port you want to forward.

Once PageKite is started, you should see output in the terminal indicating that it is running and forwarding traffic.

Test the port forwarding by accessing the forwarded port from another device or computer using the following URL:

vbnet
Copy code
http://YOURNAME.pagekite.me
