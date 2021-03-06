# Installing nsps over USB




!!! warning "Installing homebrew nsps will lead to the console ban!"
	you need to make sure you are using emunand offline or with incoginto enabled, to prevent ban on your sysnand.      
	if your console is already banned, just ignore this warning :)  


!!! tips "you need sigpatches installed on your CFW.  go to [sigpatches](/extras/sigpatches) for instructions on installing the sigpatches.  "


# Installing nsps over USB with Awoo Installer + ns-usbloader

Awoo Installer is simple installer homebrew tool for Nintendo Switch.   
More info about Awoo Installer is at [https://github.com/Huntereb/Awoo-Installer](https://github.com/Huntereb/Awoo-Installer)  


[NS-USBloader](https://github.com/developersu/ns-usbloader/releases) is a PC tool, with a fancy UI and made in Java, in order to help Awoo Installer with the remote PC option. It should work on Windows, Linux or Mac.   
Only requirement for Quark to work is Java 8u60 or above in Windows (or a very simple one) is to install [AdoptOpenJDK 11 or higher](https://adoptopenjdk.net).   
Right now, I am using Java JDK 13 from [https://www.oracle.com/technetwork/java/javase/downloads/jdk13-downloads-5672538.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk13-downloads-5672538.html)



##One time setup

1. install the sigpatches, you have not installed them before.  Read [here](/extras/sigpatches) for instructions on installing the sigpatches.  
2. Download latest `Awoo-Installer.zip` from [here](https://github.com/Huntereb/Awoo-Installer/releases)
3. extract the switch folder from `Awoo-Installer.zip` to the root of your sd card. Just overwrite your switch folder.   
4. Download latest `ns-usbloader-#.#.jar` from [here](https://github.com/developersu/ns-usbloader/releases)  
5. put `ns-usbloader-#.#.jar` in your preferred place on your computer.   
6. if you do not have JAVA JDK installed on your computer, Download Java JDK from [here](https://adoptopenjdk.net)
7. Install Java JDK on your computer. 
8. Download Zadig from [here](https://zadig.akeo.ie/)  
9. Connect your Switch via USB with your computer. 
10. Open Zadig  
11. Click "Options" and select "List all devices"  
12. Select the Switch from the drop-down menu  
13. Change the driver (right next to the green arrow) to "libusbK"  
14. Click on the button below "Install WCID Driver" or "Replace Driver"  
15. Done. Now you can use awoo installer and ns-usbloader to directly access your PC! 


## Usage of awoo installer and ns-usbloader  

1. connect your switch to your computer. 
2. open ns-usbloader on your pc and go to select file and select the nsp you want to install on your switch.   
3. open awoo installer on your switch and select install over USB. Click on ok on warning dialog. next screen should say "USB connection successful! Waiting for list of files to be sent...  
4. go to your pc and open ns-usbloader and select files to be installed to your switch.     
5. when you are done with selecting the files, click on "upload to NS" button 
6. you should see the screen with list of your files come up on your switch.  hit Y then +  to install them.   
7. the install should go well as long the files are good.   
8. enjoy your new installs.   




       
&nbsp;
