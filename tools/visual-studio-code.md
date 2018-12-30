# Using Visual Studio Code for Python development

## How to debug Python with MiniConda virtual environment

1. Install Visual Studio Code (we use 1.30.1@windows 64bit)
2. Install Python extension for Visual Studio Code (pick the one from Microsoft)
3. In Visual Studio Code, select View > Command Palette, type: python: select Interpreter , then, select the python.exe from the list. You should see your selection at the right bottom corner.
4. Now, create a helloworld.py with below content. you should get syntax help by using Ctrl-Space while editing.
msg = "Hello World"
print(msg)
5. To run above file, right click on the terminal, and select "Run Python File in Terminal".
6. To debug above file:
    * First set a breakpoint (showing as red-dot in front of the line number).
    * Next, switch to debug view (The icon looks like a bug with cross circle. It is the 4th icon located at very left of VS window)
    * Then, select Debug > Open Configurations , after a bit, launch.json is created and debuger drop down list is populated. Keep "Python: Current File (Integreted Terminal)" selected. 
    * Save and close launch.json
    * Go back to helloworld.py, select Debug > Start Debugging or F5. 

