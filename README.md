# raspberrypi-cloud-server
This repository will help to setup a raspberry pi as a cloud server to store your files in your own cloud instead of paying for cloud storage.

- To setup the Raspberry Pi, refere to [this](https://github.com/sashanknjs/raspberrypi-setup) page.

**Required Hardware:**
- Raspberry Pi any model works fine but preferably Raspberry Pi 3 or above with atleast 1GB RAM.
- SD Card (8GB or above)
- Power Adapter
- HDMI to HDMI cable (for Rasperry Pi 2,3 and 3B+) or Micro HDMI to HDMI (for Rasperry Pi 4 and 5)
- Ethernet cable
- USB Mouse and Keyboard
- Monitor (Display)
- An external USB stick according to the size of the cloud storage required.

- **OS**: Rasperry Pi OS - 32 or 64 bit (Desktop)

**Cloud Server installation**

After setting up the Raspberry Pi, you can access it either through the external monitor, SSH or VNC. SSH is the simplest method in this case since most of the installation is done using terminal commands.

- SSH into the Raspberry Pi using the command prompt in your PC.
- Once logged in, enter the following commands.
  ```
  sudo apt update && sudo apt upgrade
  ```
- Once the required updates and upgrades are installed,
