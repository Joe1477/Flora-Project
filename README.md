The project has 3 user types: observer, administrative, researcher. The observer needs to be able to submit data in as quick and efficient manner. The researcher needs to be able to retrieve the data in the excel format. The administrator needs to be able to access the database through a url.

##The observer is just gathering and submitting information: ##
* Unique ID: automated per transaction (alpha numeric) 
* Date/Time: if current timestamp else ask for date/time
* Name: 
* Plant Name: 
* Soil Type: Dropbox (limited choices)
* Weather: Text field (requirement) - (api if time allows)
* Location: Geoscope Api
* Additional: Notes

##The researcher needs to be able to quickly access via clicking on a link. ##
* (Export to excel file type)

##The administrator needs access to the database##
* Phpmyadmin login information, database built to be easily understood

To complete this setup we will be using html, css, php, and mysql. The database will be mysql as that’s what the administrator is familiar with. We will first build the front-end to gather the information, then proceed with the backend to create the database, and finally link it together. If time allows we will use an additional third party API to streamline the process.

Use Case Scenarios are attached to user Joe1477 under Flora-Project.
