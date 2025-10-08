# Network-traffic-capture-and-analysis-with-Wireshark
### Name : Sakthivel R
### Reg.No : 212222100044
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
- Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1919" height="1023" alt="Screenshot 2025-10-08 174547" src="https://github.com/user-attachments/assets/2d6f26d7-7b11-491c-97fc-fd631722528e" />


- ## Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.


<img width="1919" height="1024" alt="Screenshot 2025-10-08 175602" src="https://github.com/user-attachments/assets/69dd968c-cf5a-4a2e-a685-fc5246e8eae5" />


- ## Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.

<img width="1919" height="1023" alt="Screenshot 2025-10-08 180744" src="https://github.com/user-attachments/assets/18c41f4e-f8e1-461b-a83d-59f8c9db5e71" />



- ## Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.

<img width="1919" height="1029" alt="Screenshot 2025-10-08 181012" src="https://github.com/user-attachments/assets/29299006-c393-42be-b7ba-e566cd9af83e" />


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
