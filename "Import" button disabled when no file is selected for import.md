
# Test Case Details
ID: 5004

Name: "Import" button disabled when no file is selected for import
## Test Steps
|Step |Description | Expected Result|
|---------|----------------------|----------------| 
|1|Log in as an Org Admin|| 
|2|Select "Concept Data Types" from the sidebar on the left|Concept Data Types UI is showing, and includes an "Import Concept Data Types" link near the top| 
|3|Click on the "Import Concept Data Types" link|Import controls appear. Verify that no file is selects and the "Import" button is disabled| 
|4|Select any file (the attached file "concept\_data\_types.xlsx" is good for this test)|Verify that the "Import" button is now enabled (see it by colour)| 
|5|Press the "Choose file" button again, and click on "Cancel" in the dialoge, so no file is selected|Verify that when a file is unselected, the "Import" button becomes disabled again| 
|6|Select a file again|Verify the thhe "Import" button gets enabled again| 
|7|Click the "Cancel" button, then the "Import Concept Data Types" link, to hide than then show again the import controls|Verify that there is no file selected now, and that the "Import" button is disabled| 
|8|Select the attached file, and click on the "Import" button|Watch the import work and be successful (no errors)|