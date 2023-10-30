# CARON_medical_unit_staffing_acuity_report_project
A Power Apps application that tracks patient acuity information for patient 

### Special Note: 
The images within the application have been carefully designed to exclusively feature dummy data. No actual patient information is depicted, ensuring strict adherence to patient information protection protocols

### Project objective:
The objective of the project was to develop and publish an application that tracks acuity information for patient on Power Apps from the existing Medical Unit Staffing and Acuity Report system on excel, and setup the published application on SharePoint. The application allows the staff members to add, edit and update staffing and acuity report.

### Project scrope:
* Extracting, transforming and lodaing the medical staffing and patient acuity dataset comprising of 7000 records to SharePoint and creating a Sharepoint data source
* Connecting the Power Apps application to the SharePoint data source
* Creating four galleries on PowerApps – acuity, OT & FFS tracking, shift notes and ongoing issues
* Inserting the required and other features in the galleries
* Adding functionalities for creating new records and updating existing records by Id 
* Deploying the application on a SharePoint Page 

### Power Apps Application Interface: 4 Galleries
* The application consisted of four galleries: acuity, OT & FFS tracking, shift notes, and ongoing issues
* The first screen featured buttons for adding new records and updating existing ones
* The 'add new record' page was set as the default view for the application. 
* The 'add new record' button allows users to insert information and generate a new record number in the data source
* The 'update existing records' button enables the retrieval of information by record number from the SharePoint data source for necessary edits
* Successful creation of new records or updates generates a red notification on the screen
* Validation messages were implemented to prompt users to fill in the required fields if left blank
* Single-line and multiple-line text boxes were utilized in the galleries. Validation was set for single-line text boxes to ensure entries did not exceed 255 characters, as per SharePoint settings.
* Certain text box fields in the galleries were designated as 'number' type, and these fields were formatted to accept only numerical inputs, preventing application errors
* An error handling page was established to display users the causes of errors and the information would be stored within an error dataset in SharePoint
* An user guide tab is available in the main screen

The **pictures_application** directory includes visuals of four screens, which encompass functionalities for adding and updating dummy records, as well as demonstrating the successful creation of the records.

The **final_application_report** directory contains the final presentation that was presented to the stakeholders. It's included in this reportory with the permission of the Caron Data Analytics team.




