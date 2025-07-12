# Ethos-TriStatus-widget
An Ethos widget for displaying the Status of a source. It can display up to 3 states, like High, Medium, and Low, or 2 states like Throttle Active and Throttle Disabled.

You select a source, and then optionally define two threshold values.
- If the source value > threshold1, then State 1 will be displayed.
- If the the source value is below threshold1 but above threshold2, then State 2 will be displayed.
- If the source value is below threshold2, then State 3 will be displayed.

You can define the text and background color for all 3 states.

The default thresholds of +50.0 and -50.0 are fine for showing the status of a 3 position switch, which has values of +100%, 0% and -100%. If you select a 2 position switch, button or Logic Switch as the source, the middle state 2 will be ignored. If you select a telemetry sensor as the source, the thresholds can have values between +1000.0 and -1000.0

In my example I used Pot3 as the source. Its value can be seen as the centre slider in the screenshots.

There is a debug mode so that source and threshold values can be checked.

Currently localization is supported for CS, ES, DE, FR, and IT. Please contact me if you can assist with translation to another language. The localization files are located in the tri-status/i18n folder.

### Installation
Just copy the unzipped 'tri-status' folder to the ‘scripts’ folder on your SD card, then reboot your radio. The widget will appear as 'Tri-Status' in the 'Create widget' drop-down list when dding a widget. Assign your source, then check how your colours and labels need to be assigned under State 1,2 and 3 to give the correct indications.

![image](https://github.com/user-attachments/assets/82fe358f-0e4d-4938-b767-c239697dc6ba)

![image](https://github.com/user-attachments/assets/d26e2f5d-4747-4b21-8b6e-b755530f7698)

![image](https://github.com/user-attachments/assets/821f65bb-5ac0-4aa6-a9a2-c04ca2b5edd8)

![image](https://github.com/user-attachments/assets/cdf6f635-2fb5-4fe3-982b-8cc67effbcee)

<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/3208948e-df6d-4aa4-9960-adb9646e0784" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/47959f60-8975-4eb8-926a-4a3923849407" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/336bf834-94c3-4fde-894d-7deadbae8630" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/3d11ca17-fcee-4e70-ba25-a638f2de752a" />


<img width="800" height="480" alt="image" src="https://github.com/user-attachments/assets/e3f63414-6aad-4c30-9174-469768cf3284" />











