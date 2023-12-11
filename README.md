More info in these steps 

Automating slip generation starts by accessing your Google Sheet. Open the Extensions menu, click on "Apps Script," and insert the folder ID where the PDFs will be stored:


var salaryDetailsFolder = DriveApp.getFolderById("<id of folder where PDFs will be saved>");
```

Similarly, identify and set the template file's ID:


var salaryTemplate = DriveApp.getFileById("<id of the template document>");
```

To add a button to your sheet:

1. Go to the "Insert" tab.
2. Choose "Drawing" and select a shape for your button.
3. Draw the button on the sheet and add your preferred label.
4. Click "Save and Close" to finish creating the button.
