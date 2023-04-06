# Set-up-Raspberry-Pi
## Requirements

Raspberry Pi Imager that can be installed [here](https://www.raspberrypi.com/software/).


## Installation of Ubuntu 20.04
The first step is to flash Ubuntu 20.04 LTS on a SD card.

Download server install image for Ubuntu 20.04 64bit [here](https://old-releases.ubuntu.com/releases/focal/).
![Capture](https://user-images.githubusercontent.com/124844123/230490510-939aabca-f29b-4b40-a807-5785a488c747.PNG)

In the Raspberry Pi imager, choose the Operating System : Other General Purpose OS → Ubuntu → Ubuntu Server 20.04 64bit, and choose the SD Card, then begin to write.

When the writing is finished you can remove the SD card from the reader.

Now the SD card can be inserted in the Raspberry Pi. Do not connect the RPi to the internet for now.

Power up and see may lines scroll across your screen, after a few seconds you end up with this screen. If you are missing the prompt, or the login line, give a <enter>.

The first login is “ubuntu”, password is also “ubuntu”. Now enter a new password.

After a few lines your Ubuntu 20.04 is installed properly. Now connect the RPi to the internet, it will start updating the software in the background, wait a few minutes.

For installing the desktop without the third party applications run the command
```bash
ubuntu@ubuntu:$ sudo apt install ubuntu-desktop-minimal
```![Capture2](https://user-images.githubusercontent.com/124844123/230490941-3c916b55-d561-4a01-a9f0-9e691a96fa85.PNG)![Capture2](https://user-images.githubusercontent.com/124844123/230490966-7b18b771-1648-460a-8afd-cf33a7710506.PNG)![Capture2](https://user-images.githubusercontent.com/124844123/230490991-6e7cac29-ac18-4db8-ad59-1a90af972a94.PNG)



Once the installation finished you can access the desktop with :

```bash
ubuntu@ubuntu:$ startx
```
