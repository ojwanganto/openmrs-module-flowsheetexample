# openmrs-module-flowsheetexample
Example module for flowsheet in htmlformentryui

1. In SDK, create a new server using refapp 2.8
2. Check out latest of openmrs/htmlformflowsheetui in "flowsheet" branch, deploy this to the server
3. Build and deploy this module (flowsheetexample)
4. Start up server
5. Create a patient
6. Navigate to:  http://localhost:8080/openmrs/htmlformentryui/htmlform/flowsheet.page?patientId=PATIENT_UUID_HERE&headerForm=flowsheetexample:headertest.xml&flowsheets=flowsheetexample:visitform.xml
7. To see changes in forms in flowsheet, modify headertest.xml and visitform.xml and refresh
