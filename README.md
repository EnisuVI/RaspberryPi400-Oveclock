# RaspberryPi400-Oveclock
### Tested configuration to overclock your Raspberry Pi 400.

A configuration done and tested by EnisuVI. 

## What is it ?

If you own a Raspberry Pi 400, you may find it too slow, and that's normal. The RPI400 has a default frequency of 700MHz (0.7GHz), and that's pretty slow. Bubt if you want to improve the performances of you RPI400, you can overclock it !
By doing so, you will win approximately 30% in terms of performance. That's not impressive, but that's already better.

## What is it about ?

The goal here is to overclock your RPI400 to 2.2GHz ! To do so, you will simply need to type 1 command, replace a file and reboot your RPI. Explanations below.

## How do I do it ?

Firstly, I am not responsible IN ANY WAY if you break your Raspberry. It is your own decision to overclock it, and you do it at your own risks. You may have found some articles on the web, and there is always a disclaimer about the overclocking.
The goal of this Repository is to share to you my configuration, so that you don't have to search for every parameter.

If this doesn't work well with your machine, contact me, and I will try to help you.

So, here is the protocol :

1. Launch a Terminal on your RPI400 (Ctrl+Alt+T)
2. Type the command `sudo nano /boot//config.txt` *You can use another editor if you want, like Gedit or Geany*
3. Copy the text in `config.txt`
4. Paste to replace the whole content of the file you opened earlier
5. Save (Ctrl+S)
6. Reboot your Raspberry Pi 400 using the command `sudo reboot` in a new terminal
7. Enjoy your new settings ! If you want to check if you configuration is good, type `sudo apt install neofetch` and `neofetch`. The results should look like ![this](https://imgur.com/a/W7JCJR0).
