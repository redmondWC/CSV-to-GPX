# CSV-to-GPX
This python notebook script takes in a CSV log of time and latitude,longitude coordinates and converts it into a GPX file. See info below for modifying to fit your needs. 

0.Format of CSV file:
"serial_number","timestamp (UTC)","latDeg","latMin","latSec","lonDeg","lonMin","lonSec","speedKnots","heading","power","io1","io2","io3","io4","io51."

1.Set file names, time offsets and timestamp format
  * Set CSV file name
  * Set GPX file name
  * Confirm UTC_TO_PST shift is relevant for data collection
  * Set/confirm Timestamp format

2.Set start time (hh, mm) and end time (hh, mm)

3.Set "Serial_Number for "bus" of interest for row[0] value

4. set/confirm to reverse the order of the input file. CSV file is reverse cronological, as log files appends at the top of the csv file. The Reverse_timestamp flag will reverse this data.
