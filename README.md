# Ethos-Status-widget
An Ethos widget for displaying the Status of a source.

Here is my Status widget for showing the status of 3 states, like High, Medium, Low. You select a source, and then define two threshold values.
- If the source value > threshold1, then State 1 will be displayed.
- If the the source value is below threshold1 but above threshold2, then State 2 will be displayed.
- If the source value is below threshold2, then State 3 will be displayed.

You can define the text and background color for all 3 states.

The default thresholds of +50.0 and -50.0 are fine for showing the status of a 3 position switch, which has values of +100%, 0% and -100%. If you select a Logic Switch as the source, the middle state 2 will be ignored. If you select a telemetry sensor as the source, the thresholds can have values between +1000.0 and -1000.0

In my example I used Pot3 as the source. Its value can be seen as the centre slider in the screenshots.

There is a debug mode so that source values can be checked.

### Installation
Just copy the unzipped 'status3' folder to the ‘scripts’ folder on your SD card, then reboot your radio. The widget will appear as 'Lua Status 3'. Assign your source, then check how your colours and labels need to be assigned under State 1,2 and 3 to give the correct indications.

