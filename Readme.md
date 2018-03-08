#	This is a simple python project which introduces to python essentials
	-	I used Ecplise for this project - PyDev with python3 interpreter as the code completion option didn't work for me in VS Code. 
	-	My setup was on macOS High Sierra (10.13.1 (17B1003))
	-	What does it cover?
	1.	Topics include:
	2.	Installing Python
	3.	Choosing an editor or IDE
	4.	Working with variables and expressions
	5.	Writing loops
	6.	Using the date, time, and datetime classes
	7.	Reading and writing files
	8.	Fetching internet data
	9.	Parsing and processing HTML

#	Downloading python, sample code, IDE and configuring correct version of python:
	-	(Note: )

	1.	Install python from: https://www.python.org/
		-	Check version: python3 --version (the output should be something like this - Python 3.7.0a2 )
	2.	Install certificate: Go to-> Applications >> python 3.7 >> Install Certificates.command (double click to install)
	3.	Install IDE from: https://code.visualstudio.com/
	4.	After installing --> Launch -> click on "Extensions icon", look for the one made by Microsoft and click install.
	5.	Click on "Files" icon, Click open and browse to "Exercise Files"
	6.	After opening the "Exercise Files", click on "Debug" icon
	7.	It would say "No Configurations".
	8.	Click on "Gear Icon" next to that that and select "Python" from the drop down menu and tha will bring a "lunch.json" file.
	9.	Set the value for "cwd" to empty string, as that will ensure that the debugger points at the same directory where the python script is run from.
	10.	If you have more than 1 python version running on your machine, you need to ensure that the debugger is pointing to the right version of python. so,
		-	Code --> Preferences --> Settings --> type to search "python path" 
		-	Copy "python.pythonPath": "python" to right panel and change the value to
		-	"python.pythonPath": "python3"
		-	Save and close both.

#	Writing and executing python (All files can be executed individually and they have no dependencies on each other)
	1.	Download  "Exercise Files" and extract them to a directory.
	2.	Launch the Visual Studio(VS) Code
	3.	Click on "Files" icon and click on "Open Folder"
	4.	Browse and select on "Exercise Files" folder, and click "Open"
	5.	To Execute the files:
		-	Select each directory to step in
		-	Uncomment the code in each file and
		-	Run them to excute by clocking on "Debug" icon and "Run" icon.

# Python Documentation
	1.	Python 3.6.4 documentation: https://docs.python.org/3/
