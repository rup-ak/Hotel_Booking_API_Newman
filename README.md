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

## Documentation

- https://documenter.getpostman.com/view/26927943/2s9Y5ZwNRV





## Newman Report Summary:

![hotelbooking report 1 ss](https://github.com/rup-ak/Hotel_Booking_API_Newman/assets/93119678/28b33bc7-f9c2-4dad-b3a1-c7f6416320c0)

![hotelbooking report 1 1 ss](https://github.com/rup-ak/Hotel_Booking_API_Newman/assets/93119678/10fc12cc-a5f0-47c2-9fd3-fcde08187cf0)

and the 2nd type of report (HTML report)

![hotelbooking report 2 ss](https://github.com/rup-ak/Hotel_Booking_API_Newman/assets/93119678/8840a817-4650-4263-a720-9b3564355204)
