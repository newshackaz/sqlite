#Set-up instructions for SQLite 

Setting up SQLite on your computer is very straightforward and does not require special administrator privileges. Here’s the rundown for various operating systems:

##Windows
1. Download https://www.sqlite.org/2016/sqlite-tools-win32-x86-3100100.zip
2. Unzip the file right there in your Downloads folder
3. Test it:
  1. Open Powershell
  2. Change directories to your Downloads folder by typing the following, then Enter: `cd ~/Downloads`
  3. Start the SQLite application by typing the following, then Enter: `sqlite3`

You should see a prompt starting with “SQLite version …”
This confirms the application starts up correctly. You may exit out of Powershell.

##Mac/Linux
SQLite is already installed on Mac/Linux computers. Test it by opening the Terminal application and entering the following command: `sqlite3`
You should see a prompt starting with “SQLite version …”
This confirms the application starts up correctly. You may exit out of Terminal.

##ChromeOS
SQLite is installed on Chromebook. But it’s tricky to access -- you have to turn on Developer mode and understand all the implications of this. If you’d like to pursue this option, feel free to email directly and I’ll help you through it.

Matt Kiefer
matthewlkiefer@gmail.com

