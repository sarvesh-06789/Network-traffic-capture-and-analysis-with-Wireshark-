# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage
<img width="1909" height="1021" alt="image" src="https://github.com/user-attachments/assets/dfe4651b-f292-499e-a05d-e33318634a3b" />
2. Start Capturing Packets

<img width="954" height="1020" alt="image" src="https://github.com/user-attachments/assets/c4a85836-6123-4650-9191-b6bde6389276" />

<img width="954" height="1020" alt="image" src="https://github.com/user-attachments/assets/522666ac-eeca-4fb4-8814-fc6389303660" />
3. Apply Filters to Focus on Specific Traffic

<img width="1919" height="744" alt="image" src="https://github.com/user-attachments/assets/92814128-60bd-4f0d-bb14-4b35f63d6395" />
4. Analyze Packet Details

<img width="973" height="473" alt="image" src="https://github.com/user-attachments/assets/3ae9ea7c-32b0-4f40-9c7a-4d00673074ab" />
5.Analyse ip==10.82.65.160

<img width="1919" height="708" alt="image" src="https://github.com/user-attachments/assets/d996522d-53bd-4035-9e57-41e354cd38ca" />
6.Analyse frames

<img width="1919" height="696" alt="image" src="https://github.com/user-attachments/assets/e9dd0d18-c7b6-42d1-b02a-eb7c3553f743" />
7.Analyse tcp ports

<img width="1919" height="782" alt="image" src="https://github.com/user-attachments/assets/8b8079af-c58c-438e-b06e-d2e6885e42df" />
Export or Save the Capture

<img width="1919" height="1022" alt="image" src="https://github.com/user-attachments/assets/f3407527-0e28-457c-bdd7-dfffc497b82a" />

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
