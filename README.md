CREATE TABLE water( 
"STATE" TEXT, 
"COUNTY" TEXT, 
"FIPS" TEXT, 
"TotPop" long, 
"public" long, 
"domestic" long, 
"industrial" long, 
"crops" long, 
"golf" long, 
"livestock" long, 
"aquaculture" long, 
"mining" long, 
"thermoelectric" long, 
"total" long); 






CREATE TABLE poverty(
  "FIPS" TEXT,
  "Name" TEXT,
  "PovertyEstimate" TEXT,
  "PovertyPercent" TEXT,
  "MedianHouseholdIncome" TEXT
);
CREATE TABLE water(
  "STATE" TEXT,
  "COUNTY" TEXT,
  "FIPS" TEXT,
  "TotPop" TEXT,
  "public" TEXT,
  "domestic" TEXT,
  "industrial" TEXT,
  "crops" TEXT,
  "golf" TEXT,
  "livestock" TEXT,
  "aquaculture" TEXT,
  "mining" TEXT,
  "thermoelectric" TEXT,
  "total" TEXT
);


# #sqlite #newshackaz 
Everything you'll need to start learning command-line SQL in sunny Tucson, AZ

#Set-up instructions for SQLite 
###tinyurl.com/az-sql-setup

##Setting up SQLite
Setting up SQLite on your computer is very straightforward and does not require special administrator privileges. Here’s the rundown for various operating systems:

###Windows
1. Download http://tinyurl.com/az-sql-exe
2. Test it:
  1. Open Powershell
  2. Change directories to your Downloads folder by typing the following, then Enter: 
  `cd ~/Downloads`
  3. Start the SQLite application by typing the following, then Enter: 
  `./sqlite3.exe`

You should see a prompt starting with “SQLite version …”
This confirms the application starts up correctly. You can exit out of Powershell.

###Mac/Linux
SQLite is already installed on Mac/Linux computers. Test it by opening the Terminal application and entering the following command: `sqlite3`
You should see a prompt starting with “SQLite version …”
This confirms the application starts up correctly. You can exit out of Terminal.

###ChromeOS
SQLite is installed on Chromebook. But it’s tricky to access -- you have to turn on Developer mode and understand all the implications of this. If you’d like to pursue this option, feel free to email directly and I’ll help you through it.


## Get the data
U.S. Census poverty table by county: http://tinyurl.com/az-sql-poverty
U.S. Geological Survey water consumption: http://tinyurl.com/az-sql-water 

Make sure all files are in your Downloads folder.

References:
poverty: http://www.census.gov/did/www/saipe/downloads/estmod14/readme.txt
water: http://water.usgs.gov/watuse/data/2010/datadict.html


## Follow along
slides: http://tinyurl.com/az-sql-slides

## Email questions
matthewlkiefer@gmail.com
