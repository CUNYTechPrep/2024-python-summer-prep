
# How to setup your computer for data science in Python.  If you get errors along the way, go to the trouble shooting section first. 

# Setup for Mac Users
Here is the video tutorial I made for mac users on how to do this using the following instructions:  
Getting Setup for [python setup walkthrough video](https://drive.google.com/file/d/1-YaquavYYAHDnCCqm8ZQCR7M0h61AZAL/view?usp=drive_link).  

0. Download and install [iTerm2](https://iterm2.com/downloads.html).
1. Open iTerm2
2. Install xcode command line tools by entering the following command into your terminal (iTerm2):   `xcode-select --install`
3. Download and install [Anaconda](https://www.anaconda.com/download).  
	*  Anaconda is free. You don't have to create an account, but you do need to provide a valid email. 
	* Once you submit your email, you will be sent to another page where you pick which type of computer you have.  (Mac users make sure you [know what chip  you have](https://www.howtogeek.com/706226/how-to-check-if-your-mac-is-using-an-intel-or-apple-silicon-processor/) and choose the appropriate version for that chip.  Always choose the Graphical Installer version because it is easier. 
	* Download the Graphical Installer, and then install it like any normal application. 
4. Install homebrew via these instructions [install homebrew](https://brew.sh/)
	* Or just type in: 
		* `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
		* !! Make sure to add homebrew to your path by following the instructions it prints out after you install it. 
6. Update [git](https://git-scm.com/download/mac)
	* If you are getting a `homebrew` error you need to install homebrew. You can do so easily here [install homebrew](https://brew.sh/).
7. Download and install [Sublime Text](https://www.sublimetext.com/) and/or [VS Code](https://code.visualstudio.com/download).   

# Setup for Windows Users
---

1. Download and install [Anaconda](https://www.anaconda.com/download).  
	*  Anaconda is free. You don't have to create an account, but you do need to provide a valid email. 
	* Once you submit your email, you will be sent to another page where you pick which type of computer you have. 

2. Open up the Anaconda Powershell Terminal
	* Instructions on how to find it here --> [link](https://saturncloud.io/blog/how-to-access-anaconda-command-prompt-in-windows-10-64bit/#method-1-through-the-start-menu)
4. Download and install [git](https://git-scm.com/download/win).
	* Use the Standalone Installer not the Portable ("thumbdrive edition") installer. 

5. OPTIONAL: Download and install [Sublime Text](https://www.sublimetext.com/) and/or [VS Code](https://code.visualstudio.com/download).   


# BOTH WINDOWS AND MAC:: Once you are all setup....

 ### Wrapping up:
 * Now that we have everything installed
* Mac Users:  Fully quit iTerm (don't just close the window, but quit the application to restart it). 
* Window users: Open up your Anaconda Power Shell (in the Ananconda Folder you can find in your home menu). Or find it with help [from this tutorial](https://saturncloud.io/blog/how-to-access-anaconda-command-prompt-in-windows-10-64bit/#method-1-through-the-start-menu)
* * Type in `jupter notebook` into the terminal (iterm or Anaconda Power Shell) to launch python / jupyter
	* If that doesn't work, try `jupyter lab` instead of `jupyter notebook`
* Create a new Jupyter Notebook file, and print 'Hello World!'. 
* You're good now. Happy coding.
