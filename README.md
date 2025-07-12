# Ethos-TriStatus-widget
An Ethos widget for displaying the Status of a source.

Here is my Status widget for showing the status of 3 states, like High, Medium, Low. You select a source, and then optionally define two threshold values.
- If the source value > threshold1, then State 1 will be displayed.
- If the the source value is below threshold1 but above threshold2, then State 2 will be displayed.
- If the source value is below threshold2, then State 3 will be displayed.

You can define the text and background color for all 3 states.

The default thresholds of +50.0 and -50.0 are fine for showing the status of a 3 position switch, which has values of +100%, 0% and -100%. If you select a 2 position switch, button or Logic Switch as the source, the middle state 2 will be ignored. If you select a telemetry sensor as the source, the thresholds can have values between +1000.0 and -1000.0

In my example I used Pot3 as the source. Its value can be seen as the centre slider in the screenshots.

There is a debug mode so that source and threshold values can be checked.

### Installation
Just copy the unzipped 'tri-status' folder to the ‘scripts’ folder on your SD card, then reboot your radio. The widget will appear as 'Tri-Status'. Assign your source, then check how your colours and labels need to be assigned under State 1,2 and 3 to give the correct indications.

![image](https://github.com/user-attachments/assets/82fe358f-0e4d-4938-b767-c239697dc6ba)

![image](https://github.com/user-attachments/assets/d26e2f5d-4747-4b21-8b6e-b755530f7698)

![image](https://github.com/user-attachments/assets/821f65bb-5ac0-4aa6-a9a2-c04ca2b5edd8)

![image](https://github.com/user-attachments/assets/cdf6f635-2fb5-4fe3-982b-8cc67effbcee)

![image](https://github.com/user-attachments/assets/4dc3d44f-556c-4d8e-8ed6-e5f1daed490f)

![image](https://github.com/user-attachments/assets/a11a9f51-f6a3-42c8-8bd8-785bb2900e9e)

![image](https://github.com/user-attachments/assets/1649d510-9f46-41d6-b2d0-437071d0b9a5)

![image](https://github.com/user-attachments/assets/13ceb1e1-45b1-4a91-b4e9-5d557a5fb0e7)

![image](https://github.com/user-attachments/assets/d17aa27c-c98a-403b-9b72-4ae3bdd86b39)










