The assumpton is that you have WSL installed to your Windows desktop - VDI/View in my test case.
#WIN+R > control
Programs and Features > on left side select "Turn Windows Features on or off > Select "Windows Subsystem for Linux"
Reboot
Go to windows store and search for WSL > Install "Ubuntu" or "Ubuntu 18.04 TLS"
Follow the prompts > create account name and password





Just random BASH baby script to install ansible on WSL - assuming you are running 18.04 from Windows store.

#make the file executable
chmod +x ansibleWSL

#run privilaged
sudo ./ansibleWSL
