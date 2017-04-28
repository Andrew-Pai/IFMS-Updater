Since IFMS does not have a way to allow an user to automatically update assets, I created this script that will do it for you. 
As a custodian, when you have lots of assets to update, it is a painstaking task to have to manually update each asset. 
This script will take input in from the CSV files you specify. 
Then, by using pyautogui, look for and automatically click the correct fields to update them.


---------------------------------------------------------------------------------
Update the 'Items.csv' file with the Asset number and Location you wish to update.
The 'Location.csv' is a list of users and their corresponding location.

TO USE THIS SCRIPT:

	1.Download the 'IFMS.zip' file from the github.
	2.Open IFMS and log in.
	3.Navigate to the update items page.
	4.MAKE SURE IFMS IS NOT COVERED. Run the 'Run.bat' file.
	5.Let the script run.
	6.Note: There are 2 ways to stop the script.

Move the mouse cursor to the TOP LEFT of the screen <Recommended method
Click the command prompt and press CONTROL + C very quickly.
Currently, this script only supports updating an assets sort field and location. 
ALthough, this should be enough for what we currently need to do. If you require more functionality, please email me at akpai@edu.uwaterloo.ca