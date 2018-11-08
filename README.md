# <img src='theia.png' card_color='#40DBB0' width='50' style='vertical-align:bottom'/> THEIA IDE


## About
Installs and setup THEIA IDE localy on your Mycroft device


## Description
This skill installs Theia IDE on your Mycroft device. This makes it easy to make and edit skills for Mycroft. Thiea IDE integrates whith Github, and you can use mycroft tools like mycroft-msm and mycroft-msk directly from the integrated shell in the IDE.
Theia provides the VS Code experience in the browser. Developers familiar with Microsoft's great editor will find many familiar features and concepts, to minimze the gap when switching between desktop and cloud environment.

https://www.theia-ide.org/index.html


# INITIAL WORK !
This skill dosnt work yet!!

### What dosnt work
* Install and setup not tested yet.
cat se
### What works
* running and access to THEIA http://picroft:3000
* Therminal and use og mycroft specifik commands
* Git integration - Pull and push and monitor changes etc.
* search throu all workspaceses
* Python Language server support - formatiing and highlight etc

### Overall experiance
I like this IDE, as it is vscode like. Having it on the picroft makes it easier for me to make and edit skills etc.
Performance seems OK - dosnt see or feel anything I wouldnt expect from a IDE in thebrowser.
The git integration is awsome.

## How to install
To get Theai IDE to comile it is needed to encrease the swapsize. This is none by editing the file /etc/dphys-seapfile and setting changing CONF_SWAPSIZE=100 to 2048

to do that ssh into your device and do:
```
sudo nano /etc/dphys-swapfile
```
exit by Ctrl+X and save
And restart swarpfile
```
sudo /etc/init.d/dphys-swapfile stop
sudo /etc/init.d/dphys-swapfile start
```

## Credits
Andreas Lorensen (@andlo)

## Supported Devices
platform_mark1 platform_picroft

## Category
**Configuration**

## Tags
#theia
#IDE
#editor
#dev
