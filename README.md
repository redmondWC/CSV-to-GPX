# CSV-to-GPX
This python notebook script takes in a CSV log of time and latitude,longitude coordinates and converts it into a GPX file. See info below for modifying to fit your needs. 

0.Format of CSV file:
"serial_number","timestamp (UTC)","latDeg","latMin","latSec","lonDeg","lonMin","lonSec","speedKnots","heading","power","io1","io2","io3","io4","io51."

1.Set file names, time offsets and timestamp format
-Set CSV file name
-Set GPX file name
-Confirm UTC_TO_PST shift is relevant for data collection
-Set Timestamp format

2. Modify Hours, Minutes and Seconds to extract from CSV files
3. Set "Serial_Number for "bus" of interest for row[0] value
