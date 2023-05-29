# LogAnalysis
User Manual: Log Analysis Tool

Thank you for using the Log Analysis Tool. This user manual will guide you through the various features and functionalities available in the tool, based on the provided script.

1. Opening a Log File

Click on the "Open Log File" button to select and open a log file for analysis.
A file dialog will appear, allowing you to browse and choose the desired log file.
Once the file is selected, the tool will parse the log data and display general statistics and message ID frequencies in the corresponding text boxes.

2. Searching by Message ID

Enter a message ID in the "MsgID" entry box.
Click the "MsgID" button to initiate the search.
The search results will be displayed in the search results text box on right side.

3. Searching by Timestamp

Enter a timestamp or a range of timestamps in the "Time" entry box.
To search for a specific timestamp, enter the exact value (e.g., "123.456").
To search within a range of timestamps, use the format "startend" (e.g., "123.456789~124").
To search for a specific period (integer value), enter the period (e.g., "5").
Click the "Time" button to initiate the search.
The search results will be displayed in the search results text box.

4. Searching by Data Length

Enter a data length value or pattern in the "DataLen" entry box.(e.g., "8").
Click the "DataLen" button to initiate the search.
The search results will be displayed in the search results text box.

5. Searching for Errors

Click the "Error Search" button to search for error messages related to "chip status error active".
The search results will be displayed in the search results text box.

6. Searching by Frame/Identifier

Enter a frame/identifier search term in the "Frame" entry box.(depends on your log file it might not work !!)
Click the "Frame" button to initiate the search.
The search results will be displayed in the search results text box.

7. Searching by Device ID

Enter a device ID in the "DeviceID" entry box. (usually it is 1 or 2 )
Click the "DeviceID" button to initiate the search.
The search results will be displayed in the search results text box.

8. Viewing Search Results

The search results will be displayed in the search results text box.
You can scroll through the results using the scrollbar on the right side of the text box.

9. Additional Functionality

The tool provides general statistics, message frequencies, and load status for CAN1 and CAN2.
You can explore the general statistics and message ID frequencies in the corresponding text boxes.
The tool also supports visualization of message type frequencies, which is currently commented out in the script.
We hope this user manual has been helpful in guiding you through the Log Analysis Tool. 
Should you require any further assistance, please do not hesitate to reach out.


