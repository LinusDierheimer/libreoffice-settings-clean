# libreoffice-settings-clean

This way i can save my [LibreOffice](https://www.libreoffice.org/) settings and distribute them to others.  
I itended to make a clean and simple ux for the average user, which doesn't need full functionality like servers etc.  
  
The files are for the latest ("fresh") version of LibreOffice, but they should also work for older ones.  

Read [this](https://wiki.documentfoundation.org/UserProfile) article, to find the location for them with your version on your system.  

Steps to install on linux, mac and windows are simular, you may need to change a command name or simply do it through the file manager gui. Pretending to be inside of the config directory (user/), because from here all paths are the same on all platforms.   

`cd config/` From here the save the old settings 
`mv soffice.cfg soffice.cfg.old` Save the original setting. 
`git clone https://github.com/LinusDierheimer/libreoffice-settings-clean.git soffice.cfg/` clone my settings, thats it!  
  
Updating:  
From the `soffice.cfg` directory: `git pull`  
