# Hotel_Booking_API_Newman

How to run this project

Clone this project
Open with Postman / Command Shell
Run Command:

    newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 



Run Command for Report:

    newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra



#Technology used:

Postman
Newman

#Prerequisite:
    Jdk
    Node Js
    Newman
    Html Report Library

#Newman and Report Installation Process:

Newman Install Command:

    npm install -g newman-reporter-htmlextra



Newman Html Report Install Command:
    npm install -g newman-reporter-htmlextra

