# Gooey
SAFE Command Line GUI 

GUI application built with the tkinter module in Python. It provides a simple interface for interacting with the safe command-line utility for the Safe Network.

The application has two main functions:

"GET" - retrieves a file from the Safe Network and opens it.
"PUT" - uploads a file to the Safe Network.
The user can either enter a XorUrl in the input field and "GET", or select a file using the "Files to Put" button and "PUT". The output of the "PUT" function is displayed.

The code makes use of the subprocess module to run shell commands, and the os module to open the retrieved file. The filedialog module from the tkinter library is used for selecting a file.

Very basic, please contribute if you find it useful.

To run this code (only tested on linux), you need to have Python installed on your system. Additionally, the code uses the Tkinter module, so you need to make sure that it is installed in your Python environment.

`pip show tkinter` <br />

If the module is not installed, you can install it by running the following command:

`pip install tkinter` <br />

Should this cause an error, on Debian-derived distros you can work around it with

 `sudo apt-get install python-tk`


From a terminal you can start Gooey with: <br />
`python gooey.py`
