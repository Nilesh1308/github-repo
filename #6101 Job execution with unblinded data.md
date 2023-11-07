
# Test Case Details
ID: 6297

Name: #6101 Job execution with unblinded data
## Test Steps
|Step |Description | Expected Result|
|---------|----------------------|----------------| 
|1|Login as registered user|| 
|2|Navigate to any study program folder|| 
|3|Create **unblinded** folder under program folder or any|| 
|4|Create/Edit any of program file|| 
|5|1) Set Inputs from unblinded folder<br><br>2) Set outputs from blinded folder|Verify user will not able to run the program.| 
|6|1) Set Inputs from blinded folder<br><br>2) Set outputs from unblinded folder|Verify user will not able to run the program.| 
|7|1) Set Inputs from unblinded folder<br><br>2) Set outputs from unblinded folder|Verify user will able to run the program.| 
|8|1) Set Inputs from blinded folder<br><br>2) Set outputs from blinded folder|Verify user will able to run the program.|