# 4b_SIMULATING_TRACEROUTE_COMMAND
## DATE:27/04/2025
## AIM:
To write the python program for simulating Traceroute command
## ALGORITHM:
1. Start the program.
2. Get the frame size from the user.
3. To create the frame based on the user request.
4. To send frames to server from the client side.
5. If your frames reach the server, it will send ACK signal to client
otherwise it will sendNACK signal to client.
6. Stop the program
## PROGRAM:
```
from scapy.all import*
target = ["www.google.com"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)
```
## OUTPUT:
![Screenshot 2025-04-17 140606](https://github.com/user-attachments/assets/2a6534d4-e585-46ed-8a1d-516da6c9f883)
## RESULT:
Thus, the python program for simulating Traceroute command was successfully executed.
