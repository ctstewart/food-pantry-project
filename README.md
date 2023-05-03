# Food Pantry Digital Scanner Reader

## Description

This project reads the digital scanner at the MNSU Food Pantry and sends the data to a worker's email. It does this in the following steps:

1. Read the scanner using a RS232 to USB converter on a button press
2. Parse the data using a python script running on a Raspberry Pi
3. Save the data to an Excel file
4. Send the data to an MNSU Food Pantry worker's email at the end of the day
