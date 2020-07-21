# Demo Title

How to install Ubuntu bash on Windows 10 only.
Note: Make sure you are connected to internet.

# Steps

## 1. Go to windows app store
- > Login with Microsoft Account ( ignore if already did ) 
- > search for "Ubuntu " -> Hit get button. 
- > it will require 432 MB of data to get installed.
- > Do not open Ubuntu for now.

## 2. Press windows key and type " Turn windows features on or off" , hit enter
- > in the list search for " windows subsystem for linux " , tick on, press ok. 
- > windows will suggest you to reboot the pc -> Hit enter.
- > You will see update in progress screen. It is totally fine.

## 3. After turning on, run Ubuntu App.
- > For the first time it will show - " Installing this may take few minutes ", Please wait.
- > After that, you will see " Enter new UNIX username " on screen.
- > Enter the username with your choice and hit enter.
- > Enter new password, hit enter
- > Retype the password, hit enter

### Here you are Done with installation.

## For the first time It is advisable to install updates of ubuntu distribution.
- > 1. "sudo apt update" 
- > 2. "sudo apt upgrade"

## where does ubuntu on windows store files ?
- > C:\Users\your-windows-user-name\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_79rhkp1fndgsc\LocalState\rootfs\home\unix-user-name

## How to get the address of your windows desktop on Ubuntu bash ?
- > cd /mnt/c/users/your-windows-user-name/Desktop

## Author

* **Rohit Kolapkar** - [rohitkolapkar](https://github.com/rohitkolapkar).

## Thank you. 
 
