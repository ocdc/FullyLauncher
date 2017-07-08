# FullyLauncher
To use:
- Host the file somewhere.
- Link to the file with the query string package action and url. Only package is required.
- Package names can be found on the id part of the query string in the google Play App store.

## Example Usage
If you want to open the SmartThings app, go to the Google play store page:
https://play.google.com/store/apps/details?id=com.smartthings.android&hl=en_GB

Look for the text in the id part of the query string:
com.smartthings.android

Host the html file somewhere (it's plain HTML with no dependencies so any simple hosting will do), then use the link (where mywebhost.com is your chosen host):
https://mywebhost.com/fullyLoader.html?package=com.smartthings.android