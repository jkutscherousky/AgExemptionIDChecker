# AgExemptionIDChecker
Checks the Agriculture Exemption ID for ABC auto

This script was written by Justin Kutscherousky on 01/01/2016 for ABC Auto Parts. The purpose of this script is
to automate the checking of agriculture exemption IDs on the website "https://mycpa.cpa.state.tx.us/regagexsearch/RegAgexSearch.do" 

For this script to work properly you must have a text document in list form of the exemption codes you wish to check. This document must be in the same directory as the script itself and must be named "agAccounts.txt". The script will generate a text file titled "idResults.txt". This text file will have the word "PASS" if the code is still valid, "FAIL" if the code is no longer valid, and "INVALID" if the input into the text box on the website was not an eleven digit number. There will also be a date that follows this, this is the "end date" for the tax exemption code.
