# Hotel_Booking_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command: 

```console 
newman run HotelBooking.postman_collection.json -e HotelBooking.postman_environment.json
```


- Run Command for Report: 
```console 
newman run HotelBooking.postman_collection.json -e HotelBooking.postman_environment.json -r cli,htmlextra
```


## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```







## Newman Report Summary:

![image](https://github.com/rup-ak/Hotel_Booking_API_Newman/assets/93119678/87e6dc4c-9388-42b1-8ab2-06ff76a02e56)

![image](https://github.com/rup-ak/Hotel_Booking_API_Newman/assets/93119678/1b091748-f658-4b3d-a445-35edcbada210)
