# **python_for_pastors**
Python tools that are free for pastors to use.

# **Tool 01: Powerpoint_Images_to_Slides.py**
  Easily generate slides with one full bleed image per slide. Just provide a path to the folder where the images are stored.

## **Step-by-Step Setup**\
\
**1. Install Python:**\
a. Ensure that Python is pre-installed on your system. Most macOS versions come with Python pre-installed (not true of Windows), but you can check by opening.....
       
    Command Prompt on PC (Windows key + type cmd).....or.....Terminal on Mac OS (found in Applications > Utilities)
.....and typing:\
        
    python3 --version
b. If Python is not installed, you can download it from https://www.python.org/downloads/.
\
\
**2. Install Required Libraries:**\
a. If Python is installed, in the Terminal run the following command to install the necessary libraries:\

    pip3 install python-pptx pillow
b. This command installs the python-pptx and Pillow libraries, which are required for the script to work.\
\
\
**3. Create the Script File:**\
a. Open a text editor, like.....

       Notepad on PC....or.....TextEdit on Mac
.....and copy/paste the script Powerpoint_Images_to_Slides.py to the text editor.\
b. Save the file as Powerpoint_Images_to_Slides.py. Make sure to select "Plain Text" format in Notepad/TextEdit to avoid any formatting issues.\
\
\
**4. Create a Simple Launcher:**\
a. Create a simple double-click script.\
b. Open a new text file in TextEdit and add the following lines to the file:
    
        #!/bin/bash
        python3 /path/to/your/Powerpoint_Images_to_Slides.py
c. Replace /path/to/your/create_presentation.py with the actual path where you saved the Python script.\
d. Save this file as Run_Powerpoint_Images_to_Slides.sh and make sure to select "Plain Text" format.\
\
\
**5. Make the Shell Script Executable:**\
a. Open a terminal.\
b. In the Terminal window, type cd (with a space after cd), then drag and drop the folder (location of the .sh file) from.....
    
       Windows Explorer on PC.....or.....Finder on Mac OS
.....into the Command Prompt/Terminal window.\
c. This will automatically insert the path to that directory.\
d. Press Enter to change to that directory.\  
e. Run the following command to make the script executable:
    
        chmod +x Run_Powerpoint_Images_to_Slides.sh
\
\
**6. Running the Script:**\
a. Now, you can simply double-click the Run_Powerpoint_Images_to_Slides.sh file to execute the script. It will prompt them to enter the folder path\
containing the images, and then it will create the PowerPoint presentation.
