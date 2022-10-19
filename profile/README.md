## <img src="Logo3.png" alt="logo" width="25" height="25"/> Hi there 👋


NET-RMSI (Networked remote management server interface) is a opensource, cheap to deploy alternative to traditional enterprise solutions commonly found on server hardware that consumer hardware lacks.

The project consists of many different applications that work together to allow remote management of consumer servers and computers:
- [NET-RMSI_Client](https://github.com/NET-RMSI/NET-RMSI_Client) - The software which is deployed on the microcontroller embedded in the actual hardware.
- [NET-RMSI_SRV_Py](https://github.com/NET-RMSI/NET-RMSI_Srv_Py) - The software which is deployed on the server hardware such as a raspberrypi. The server manages communication between controller and controlled clients along with storing connection information as well as versioning checking.
- [NET-RMSI_Bot](https://github.com/NET-RMSI/NET-RMSI_Bot/) - The software which allows for the server to be controlled through a discord/slack integration.
