# WIS_WebDeployHelper
A tool for greatly facilitating web deployment with LiveCode 10

## Updates
1.0.2 (13 May 2024)
- Enhancement: It is now possible to use the built-in Test function to deploy locally and still get all the advanced features (the html file is added to the Copy files section in the standalone builder)
- Enhancement: Verdana (plain, bold, italic) added to web font CSS code
- Enhancement: Build folder no longer opens automatically on Create, to prevent stacking up of folder windows. Open it manually if needed by clicking the url in the event log. 
- Other minor fixes

## Description
This tool helps you make a more functional web deployment of a LiveCode stack than you can get with just the native standalone builder.

The current version can help you do the following:
- Modify the appearance of the web page that the LC stack resides on (your own logo, background colour etc)
- Add code that will make the stack resize when the browser window is resized, or make the stack stay centered on the web page
- Add code that enables pasting into fields and putting text into the clipboard (not in mobile browsers)
- Add code that enables mouse wheel scrolling in all LC fields and relevant widgets (not in mobile browsers)
- Add code that gives you access to the localStorage functionality, which enables saving data between sessions
- Add code that enables uploading of file data from your local files (like image data and text)
- Other minor nifty features :) 

It also helps automating the deployment process, so that you with one click can get the standalone built and uploaded by ftp to your server.

To be of any use, this stack requires LiveCode v10.0.0 dp7+ to run, and a web deployment license for LC10. Apart from that it only uses standard LiveCode controls and widgets.

This tool is free of charge, but if you like my work and want to suppport it you can buy me a coffee: https://www.buymeacoffee.com/riu9yazy7p
