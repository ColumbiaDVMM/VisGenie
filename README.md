##VisGenie
____
####Terms of Use

Copyright (c) 2002 by DVMM Laboratory

Department of Electrical Engineering</br>
Columbia University</br>
Rm 1312 S.W. Mudd, 500 West 120th Street</br>
New York, NY 10027</br>
USA


Please see http://www.ee.columbia.edu/ln/dvmm/downloads/dvmmVisGenie.htm for details.

####System Requirements

#####Basic 
 Intel Pentium processor</br>
 Microsoft Windows Me / 2000 / XP</br>
 128MB of RAM </br>
 30MB of available hard-disk space </br>
 Microsoft Internet Explorer 5.5 or higher </br>

#####Advanced
 Microsoft Visual C++ 6.0 or higher</br>
 Mathworks Matlab 6.0 or higher</br>
 Microsoft DirectX SDK</br>


####Installation Instruction

The installation of VisGenie is very simple. Just double click on the downloaded file and follow the instruction provided during the installation. Make sure you have the Administrator right. 

If you want to uninstall VisGenie, go to ""Start Menu\Programs\VisGenie", and choose "Uninstall".

####Package Content

After you have installed the VisGenie package successfully, the following items have been added to your system:

The application folder, at "C:\Program Files\VisGenie" by default or your specified position.

The start menu folder, at "Start Menu\Programs\VisGenie" by default or your specified name.

If you have Microsoft Visual C++ 6.0, VisGenie will add a VisGenie AppWizard at: "[VStudio]\Common\MSDev98\Template\VisGenieAppWizard.awx", where [VStuidio] is the path you installed your Microsoft Visual Studio in, usually "C:\Program Files\Microsoft Visual Studio\". If for any reason you can't find the file, you can find a backup copy from your application folder. Just copy it manually to the place indicated above.

For more information on how to use VisGenie, please refer to Instant VisGenie.

####System Configuration

#####Microsoft Visual C++:
	
Make sure the VisGenie AppWizard has been copied into your Visual Studio successfully. Please see Package Content above for details.

	
Add the VisGenie header file directory into your Visual C++. 

If you are using Visual C++ 6.0, follow these steps: 
 Go to menu item "Tools / Options... / Directories", 
 Under the text "Show directories for:", choose "Include files". 
 In the directories list, choose "New" button. 
 Click on the "..." button, browse into the directory "[VisGenie Folder]\INCLUDE" and click "OK". 
 Click "OK" to exit the setting. 

If you are using Visual C++.NET, follow these steps: 
 Go to menu item "Tools / Options...", 
 Click on "Projects / VC ++ Directories ". 
 Choose "Include Files" in "Show Directories for:"
 Add the directory "[VisGenie Folder]\INCLUDE" and click "OK". 
 Click "OK" to exit the setting.


#####Mathworks Matlab: 

Add the Matlab header and library file directories into your Visual C++. (The following instruction is based on Matlab 6.5. For other Matlab version, the exact directory may vary.)
	
Following the ways mentioned above to add the Matlab header files into Visual C++. The Matlab header files are located at: "[Matlab Folder]\extern\include".
	
Following the similar ways mentioned above to add the Matlab library file directory into Visual C++. The only difference is to choose "Library files" instead of "Include files" in "Show directories for:". The Matlab library files are located at: "[Matlab Folder]\extern\lib\Win32\Microsoft\VC60"(Visual C++ 6.0) or "[Matlab Folder]\extern\lib\Win32\Microsoft\VC70" (Visual C++.NET).

Make sure the Matlab library directory has been added into your Windows system. Choose "Start menu / Control Panel / System / Advanced", and click on the "Environment Variables" button. Check both the "User variable for [UserName]" and "System Variables" sessions. Make sure for at least one of the sessions matlab library directory ("[Matlab Folder]\bin\win32") is included in the "Path" variable value.This should have been set during your Matlab installation. In any case you can't find it, double click on the "Path" variable, add add the directory. After your adding, you need to reboot your system to activate your change. 

If you want to use your own Matlab script files or functions, make sure the directories containing these files have been added to Matlab searching paths.
