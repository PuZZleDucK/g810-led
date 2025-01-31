# g810-led

Linux LED controller for the Logitech G810 Orion Spectrum Keyboard

Other compatible keyboard :</br>
G410 Atlas Spectrum</br>
G610 Orion</br>
G910 Orion Spark</br>
G910 Orion Spectrum

![jj](https://raw.githubusercontent.com/MatMoul/g810-led/master/pictures/logitech_g810-2.jpg)

### Install and use :</br>
```
sudo apt-get install g++ libusb-dev libusb-1.0-0-dev libusb-1.0-0 make
make
cp bin/g810-led /usr/bin
```

### More info
- look at the wiki : https://github.com/MatMoul/g810-led/wiki

### Samples :</br>
`g810-led -p /etc/g810/profile # Set a profile`</br>
`g810-led -k logo ff0000 # Set color of a key`</br>
`g810-led -a 00ff00 # Set color of all keys`</br>
`g810-led -g fkeys ff00ff # Set color of a group of keys`</br>
`g810-led -s color # Set keyboard power on effect`</br>

### Samples with no commit :</br>
`g810-led -an 000000 # Set color of all key with no action`</br>
`g810-led -gn modifiers ff0000 # Set color of a group with no action`</br>
`g810-led -kn w ff0000 # Set color of a key with no action`</br>
`g810-led -kn a ff0000 # Set color of a key with no action`</br>
`g810-led -kn s ff0000 # Set color of a key with no action`</br>
`g810-led -kn d ff0000 # Set color of a key with no action`</br>
`g810-led -c # Commit all changes`</br>
