# Ethos-TriStatus-widget
An Ethos widget for displaying the Status of a source. It can display up to 3 states, like High, Medium, and Low, or 2 states like Throttle Active and Throttle Disabled.

You select a source, and then optionally define two threshold values.
- If the source value > threshold1, then State 1 will be displayed.
- If the the source value is below threshold1 but above threshold2, then State 2 will be displayed.
- If the source value is below threshold2, then State 3 will be displayed.

You can define the text, the background color for all 3 states, and now also the text color.

The default thresholds of +50.0 and -50.0 are fine for showing the status of a 3 position switch, which has values of +100%, 0% and -100%. If you select a 2 position switch, button or Logic Switch as the source, the middle state 2 will be ignored. If you select a telemetry sensor as the source, the thresholds can have values between +1000.0 and -1000.0

In my example I used Pot2 as the source. Its value can be seen as the S2 slider in the screenshots.

There is a debug mode so that source and threshold values can be checked.

Currently localization is supported for CS, ES, DE, FR, and IT. Please contact me if you can assist with translation to another language. The localization files are located in the tri-status/i18n folder.

### Installation
Just copy the unzipped 'tri-status' folder to the ‘scripts’ folder on your SD card, then reboot your radio. The widget will appear as 'Tri-Status' in the 'Create widget' drop-down list when adding a widget. Assign your source, then check how your colours and labels need to be assigned under State 1,2 and 3 to give the correct indications.

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/34511644-bad2-4574-ae37-01f9c9bb98a7" />

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/48de5588-3b0b-422b-bb33-d6d6aee1ff73" />

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/f3ad702a-c16c-4cce-9e71-9b76913ffe04" />

![image](https://github.com/user-attachments/assets/cdf6f635-2fb5-4fe3-982b-8cc67effbcee)

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/b2881b3a-292d-4a4b-b377-220163fc7f57" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/5d59a69c-b654-4bd8-b8ec-8645e97b9d23" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/0c5b4c06-2679-4b41-999f-3aa41fd1e09e" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/15f4f776-79c4-4d6d-a1a2-1902bcc65d33" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/9830b561-5426-4071-a82b-2049970f7969" />

Example with different text color:

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/9c7720b5-9902-4139-8757-d547a09be826" />











