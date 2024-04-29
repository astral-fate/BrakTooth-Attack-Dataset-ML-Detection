# BrakTooth-Attack-Dataset-ML-Detection

- OBEX (Object Exchange) & Hijaking: Typically used for file transfers over Bluetooth. While not directly related to process manipulation, if a vulnerability in OBEX is exploited, it could potentially be used to transfer malicious files or payloads which could execute process hijacking or DLL injection attacks.

- LMP (Link Management Protocol) & process-based attacks: Manages link setup and control in Bluetooth. Exploiting LMP could potentially allow an attacker to compromise the device at a lower communication layer, which might indirectly facilitate process-based attacks if the device's security integrity is compromised.

- HCI_EVT (Host Controller Interface Events) and HCI_CMD (Host Controller Interface Commands): These protocols handle the commands and events between the host and the controller. Exploiting these could, in theory, allow an attacker to send malicious commands or intercept events, but linking this directly to process manipulation would be more circumstantial and less direct.

- RFCOMM: A protocol used for emulating serial port connections over L2CAP. Vulnerabilities here might allow unauthorized execution of commands or data exchange, which could be used as part of a multi-stage attack involving process manipulation.

- L2CAP (Logical Link Control and Adaptation Protocol): Handles multiplexing data between different higher layer protocols. An exploit here might indirectly affect system stability or data integrity, potentially creating a vector for further attacks, including process manipulation.
  
- Baseband, SDP (Service Discovery Protocol), HCI H4 Broadcom, and BNEP (Bluetooth Network Encapsulation Protocol): These protocols handle various fundamental tasks in Bluetooth communications and device services. While exploits in these areas could lead to initial system access or denial of service, their direct involvement in process manipulation attacks like those listed would be less straightforward and more about creating an initial breach to leverage more targeted exploits.

OBEX (Object Exchange): A communication protocol that facilitates the exchange of binary data over Bluetooth.
LMP (Link Manager Protocol): Manages and controls links between Bluetooth devices at the lower layers of the Bluetooth stack.
HCI (Host Controller Interface), including HCI_EVT (Events), HCI_CMD (Commands), and HCI H4 Broadcom: Provides a command interface for the host to interact with the Bluetooth hardware, specifying commands, events, and data forms that pass between the host stack and the controller.
RFCOMM: A simple set-and-forget protocol that emulates the serial port over Bluetooth.
L2CAP (Logical Link Control and Adaptation Protocol): Facilitates data transmission between devices over Bluetooth, handling segmentation and reassembly of packets.

## Refrences 
https://onlineacademiccommunity.uvic.ca/isot/2023/05/30/iot-security-datasets/

https://www.kaggle.com/datasets/blackarcher/malware-dataset?resource=download
