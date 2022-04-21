# iOS-Shortcut-Updater
A self hosted alternative to using Routinehub for updating your shortcuts! 


Provide update support without relying on RountineHub - directly from a GitHub repo or own website! 


# How to use

1. Download the Shortcut Updater -  [Shortcut Updater](https://www.icloud.com/shortcuts/d45829a19a8e422a9c643e3d09541f08) 
 

2. Create a JSON file with the following contents

        {"url":"YOUR_CLOUDLINK_URL", "version":"1.0"}

3. Host the .json file (in a github public repo or your own website etc.) 

4. Add a comment with the text "*MergeCuts*" (No quotation marks) into your shortcut where you would like to check for updates! 

5. Use MergeCuts to merge your shortcut together with the "Shortcut Updater" as the first file.

6. Create a iCloud link with your new shortcut from MergeCuts.

7. Edit the .json file - change the Version # & replace the ICloud Link with your own!

8. Edit the dictionary in "Shortcut Updater" to match the version you set in the .json file.

9. Replace the current URL in "Shortcut Updater" shortcut with the link to your json file!

(To test to make sure things are working - change the current version to less than the version you set your JSON file & the updater page will be shown!)


## Extra
On first run you can redirect user to a page where you can track vistor / download count. 
