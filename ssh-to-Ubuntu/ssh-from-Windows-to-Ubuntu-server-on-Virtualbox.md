## How to ssh from Windows 10 to Ubuntu-server on Virtualbox?
1. Install Ubuntu-server on Virtualbox with all default settings.
2. Go to "Settings--> Network" of of Ubuntu-server on Virtualbox. Set the "Attached to" to "Bridged Adapter".![](./ubuntu-server-virtualbox-setting.jpg "")
3. Get the ip address of ubuntu-server using ifconfig command.![](./ubuntu-server-virtualbox-ifconfig.jpg "")
4. Launch cmd prompt on host Windows10 and fire ssh username@ipaddress. ![](./ssh-from-windows10-cmd-to-ubuntu-server.jpg)
