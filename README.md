# KoboToolbox-GoogleApps-Scripts-DownloadNew
A modified version of the InitSurvey function for the https://github.com/pcurrier/KoboToolbox-GoogleApps-Scripts script to download only new Kobo Data.
The original script, as of 28/05/19 downloads all of the data each time it is run, meaning we need to delete the existing data in the Google sheet before downloading new data. This script is designed for larger datasets so if you know the existing data hasn't changed, then you will only download the new data.

Each time there are any changes in the KoBo data itself, the whole dataset should be deleted from the Google sheet anyway in order to make sure our data in the google sheet is correct.

Instructions:
1) set up the google sheet to download the Kobo data as described in https://github.com/pcurrier/KoboToolbox-GoogleApps-Scripts
2) After setting up your correct account settings, head to Survey.gs and delete all of the InitSurvey function. 
3) Copy the code from InitSurvey.js
4) Paste it into Survey.gs and save the .gs file
5) Refresh the GoogleSheet
6) Run a few tests to make sure it is working properly (delete a line from the googlesheet for example)
