Installing and configuring Sublime on your home Windows computer
=============================

To duplicate the Sublime configuration we use at school on your home computer you will need to install several different programs and configure the Windows path variable.

Install Processing
------------------
1. Download [Processing](https://processing.org/download/?processing). On the school computers we are using the 64 bit version of Processing 3
2. Extract the compressed folder. It will be named something like `processing-3.3.4-windows64.zip`. One way is to right click on the folder and choose *Extract All*
3. The extracted folder will have a name like `processing-3.3.4`. Move the folder to a convenient location. One place might be `C:\Program Files`.

Configure the Windows path variable
---------------
1. Open Windows *System Properties*
2. One way is to go to the bottom left of the screen and in the field labeled *Type here to search* type `sysdm.cpl` and press enter  
![sysdm.cpl](SublimeConfig3.png)
3. In the *System Properties* window, click on the *Advanced* tab
4. Click on the *Environment Variables* button
5. Under *System Variables* scroll down and choose *Path.* Then click on *Edit*  
6. Click on *New* and then type the path to Processing. It should look something like `C:\Program Files\processing-3.3.4`  
![sysdm.cpl](SublimeConfig4.png)
7. Click on *Ok* and *Ok* to exit

Install GitBash
---------------
1. Go to [https://git-scm.com/downloads](https://git-scm.com/downloads) and click on *Windows* under *Downloads*.
2. Double click the downloaded file. It will have a name like `Git-2.14.1-64-bit.exe`.
3. Click *Yes* to run the installer
4. The default configuration works fine, you can click *Yes* or *Next* whenever prompted

Install Sublime Text 3
---------------
1. Go to [http://www.sublimetext.com/3](http://www.sublimetext.com/3) and download Sublime Text 3 for Windows. 
2. Double click the downloaded file. It will have a name like `Sublime Text Build 3143 x64 Setup.exe`.
3. Click *Yes* to run the installer
4. The default configuration works fine, you can click *Yes* or *Next* whenever prompted. (Optional: On the school classroom computers *Add to explorer context menu* was selected on the *Select Additional Tasks* screen)

Install Package Control and the Processing plugin for Sublime
---------------
1. In Sublime, choose *Tools | Install Package Control*
1. Choose *Preferences | Package Control*
2. Click on *Package Control: Install Package*
3. Type *Processing* in the text field
4. Click on *Processing* to install the plugin
5. Look at the bottom left of the Sublime program to see if the plugin installed correctly. If not, just install the Processing plugin again.

Configure the Processing plugin for Sublime
---------------
1. In Sublime choose *Tools | Build System | Processing*
2. Choose *Tools | Build With...* and click on Processing
3. Choose *View | Syntax | Processing*

