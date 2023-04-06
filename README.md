# Set-up-Raspberry-Pi
## Requirements

Raspberry Pi Imager that can be installed [here](https://www.raspberrypi.com/software/).


## Installation of Ubuntu 20.04
The first step is to flash Ubuntu 20.04 LTS on a SD card.

Download server install image for Ubuntu 20.04 64bit [here](https://old-releases.ubuntu.com/releases/focal/).
![Capture](https://user-images.githubusercontent.com/124844123/230490510-939aabca-f29b-4b40-a807-5785a488c747.PNG)

In the Raspberry Pi imager, choose the Operating System : Other General Purpose OS → Ubuntu → Ubuntu Server 20.04 64bit, and choose the SD Card, then begin to write.

![Capture2](https://user-images.githubusercontent.com/124844123/230491201-9cc7a56f-b5d2-4251-bd45-5e7ed07e047a.PNG)

When the writing is finished you can remove the SD card from the reader.

Now the SD card can be inserted in the Raspberry Pi. Do not connect the RPi to the internet for now.

Power up and see may lines scroll across your screen, after a few seconds you end up with this screen. If you are missing the prompt, or the login line, give a <enter>.
  
![Capture3](https://user-images.githubusercontent.com/124844123/230491401-16e7fc76-1e00-42aa-b343-59e063ed75c7.PNG)

The first login is “ubuntu”, password is also “ubuntu”. Now enter a new password.

After a few lines your Ubuntu 20.04 is installed properly. Now connect the RPi to the internet, it will start updating the software in the background, wait a few minutes.

For installing the desktop without the third party applications run the command
```bash
ubuntu@ubuntu:$ sudo apt install ubuntu-desktop-minimal
```



Once the installation is finished you can access the desktop with :

```bash
ubuntu@ubuntu:$ startx
```
