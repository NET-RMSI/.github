# NET-RMSI (Networked Remote Management Server Interface)
NET-RMSI is an open-source and cost-effective alternative to traditional enterprise solutions commonly found on server hardware that consumer hardware lacks. The project consists of different applications that work together to allow remote management of consumer servers and computers.

## Applications
[NET-RMSI_Client](https://github.com/NET-RMSI/NET-RMSI_Client)
This is the software deployed on the microcontroller embedded in the actual hardware. It allows for remote management of the hardware by sending and receiving commands from the server.

[NET-RMSI_SRV_Py](https://github.com/NET-RMSI/NET-RMSI_Srv_Py)
This is the software deployed on the server hardware, such as a Raspberry Pi. The server manages communication between the controller and controlled clients, along with storing connection information and version checking.

[NET-RMSI_Bot](https://github.com/NET-RMSI/NET-RMSI_Bot/)
This is the software that allows the server to be controlled through a Discord/Slack integration. It provides an interface for sending commands to the server through a chatbot.

## Getting Started
To use NET-RMSI, follow the steps below:

Install the appropriate client software on the hardware you wish to manage remotely.
Install the server software on a Raspberry Pi or similar device.
Configure the client software to connect to the server.
Use the NET-RMSI Bot to send commands to the server and manage the hardware remotely.

## Contributing
NET-RMSI is an open-source project, and contributions are welcome. To contribute, please fork the repository and submit a pull request with your changes.

## License
NET-RMSI is licensed under the MIT License. See the LICENSE file for more information.