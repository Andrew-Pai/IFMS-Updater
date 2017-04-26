Since IFMS does not have a way to allow an user to automatically update assets, I created this script that will do it for you.
As a custodian, when you have lots of assets to update, it is a painstaking task to have to manually update each asset.
This script will take input in from the CSV files you specify. Then, by using pyautogui, look for and automatically click the correct fields to update them.

TO USE THIS SCRIPT:
First download the 'IFMS.zip' file from the github.
Open IFMS and log in.
Navigate to the update items page.
Then  run the 'Run.bat' file.
It'll then ask you for the directory of the Loaation and Item file. Just input the location of the file, should just be: 'Location.csv' and 'Items.csv'.
Then let the script run.

Note: There are 2 ways to stop the script.
  1. Move the mouse cursor to the TOP LEFT of the screen <Recommended method
  2. Click the command prompt and press CONTROL + C very quickly.

Currently, this script only supports updating an assets sort field and location. ALthough, this should be enough for what we currently need to do.
If you require more functionality, please email me at akpai@edu.uwaterloo.ca
