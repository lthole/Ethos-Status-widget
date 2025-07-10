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

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a16848241-196-screenshot-2023-01-08-52584.png![image](https://github.com/user-attachments/assets/569e7f3d-fdfb-41f7-89f1-76bac1cbbc8f)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a16848243-14-screenshot-2023-01-08-52594.png![image](https://github.com/user-attachments/assets/34dd0c9a-c487-4714-b50c-7584c008d8e8)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a16848245-204-screenshot-2023-01-08-52836.png![image](https://github.com/user-attachments/assets/58b1dba4-7382-423d-bb92-619a577693ef)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a16848247-162-status3.png![image](https://github.com/user-attachments/assets/79776c6a-f77f-4345-816b-7ca53f5cdcda)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a18161421-150-screenshot-2024-03-23-49955.png![image](https://github.com/user-attachments/assets/e01ef24f-7dc3-4cba-b945-1a269de793d0)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a18161657-84-screenshot-2024-03-23-58914.png![image](https://github.com/user-attachments/assets/e05bc338-b449-4ab5-b7fb-83713aa0e855)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a18161665-104-screenshot-2024-03-23-59446.png![image](https://github.com/user-attachments/assets/e4e57d49-9fe9-42e1-811b-d1b690ebf5d9)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a18161663-10-screenshot-2024-03-23-59440.png![image](https://github.com/user-attachments/assets/2dcd303b-ffe5-4786-b3b9-8e0a1343274c)

https://static.rcgroups.net/forums/attachments/3/5/0/2/6/a18161661-0-screenshot-2024-03-23-59433.png![image](https://github.com/user-attachments/assets/30b530f2-23bb-4753-9b5d-2959d5d8015d)








