# APRS-SmartBeaconing-Worksheet
Spreadsheet to help visualize APRS SmartBeaconing parameters in a Byonics TinyTrak APRS tracker.

The spreadsheet was created using MS-Excel in Office 2010, but can be used in LibroOffice.

Calculations based on the description of the SmartBeaconing algorithm described at www.hamhud.net (Nov. 2015).

Enter your parameters in the yellow fields on the Beacon Rate worksheet.<br>
The calculations are performed on a MPH basis (it's what my tracker happens to use) then graphed in terms of both miles and kilometers for comparison.

The speed range can be increased simply by redefining the maximum value for the horizontal Speed axis scale.<br>
In the case of the Turn Threshold chart, the both primary and secondary axes' scales were chosen to align both
the deg-mph and deg-km/h turn threshold so that these could can be represented by a single line on a single chart. (Works in MS Excel.)

The combined MPH-KM/H Turn Threshold chart on the Beacon Rates tab causes problem for LibreOffice. The KM/H Turn Threshold
becomes aligned to the MPH scale but is otherwise correctly represented on this scale as if were a KM/H scale. 

The Alternate Charts tab contains separate MPH and KM/H charts for the Turn Threshold that will render correctly in LibreOffice.
Other differences between Excel and LibreOffice seem to be cosmetic rendering problems with the charts.

Change Log:
Nov. 10, 2015 - tdel - initial version<br>
Nov. 20, 2015 - tdel - show both MPH and KM/H
