# LatitudeLongitudeConversion

Changed to not use the Excel macro. Using separate columns to enter degrees, minutes, and seconds. Does
not require the use of a macro to extract the fields from one column entry.

The formulas in the second sheet convert those columns to degree.decimal format.

*** ----------- below is original method ---------------
EXCEL macro to convert from degree/minute/second/direction to Degree.decimal notation

Old school VBA function used to convert degree/minute/second/direction to degree.decimal notation. 

The included excel spreadsheet uses the function to convert and move the values to a second sheet. This is then saved as a .csv file for input into an online conversion program (ex: InterNTN) to create a .gpx file which can then be used as input to a routing program such as OpenCDN. The .gpx file can also be used as input to chartplotters, etc.

