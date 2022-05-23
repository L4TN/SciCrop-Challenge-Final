# SciCrop Geolocalizations-App Challenge
This repository has the objective of elaborating and solving the challenge proposed by the company SciCrop by creating an application that meets the requirements set out below:

| Functional Requiriments                | Non-Functional Requiriments                                   | 
| :----------------------:               | :----------------------------------------------------------:  | 
| User can register a new Location       | The system must run on web platform (Portability)             | 
| List     Locations                     | The system must use a Javascript library (Implementation )    |                                               
| View Locations in Map                  | the system must persist data. (Interoperability) | 


## Software Architecture & System Architecture
![Microservices Image](https://user-images.githubusercontent.com/75400361/169652789-c16708cb-dd6e-4abb-b030-1d6dc566ace9.png)


## Install Golang
Make sure you have Go 1.18 or higher installed.

https://golang.org/doc/install

## Install CORS Unblock for your browser

Edge: https://microsoftedge.microsoft.com/addons/search/cors

## Environment Config

Set-up the standard Go environment variables according to latest guidance (see https://golang.org/doc/install#install).

## Installation
```bash
# Download this project
git clone https://github.com/L4TN/SciCrop-Challenge-Final.git
```

## Run BackEnd API
```bash
# Build and Run
cd ./SciCrop-Challenge-Final/src/BackEnd
go build
go mod tidy
go run .
```

## Run FrontEnd 
cd ./SciCrop-Challenge-Final/src/FrontEnd
open index.html


# API Endpoint : http://localhost:8080/locations
```

## Todo

- [x] Construct Front-End CRUD with Leaflet.js
- [x] Support basic REST APIs.
- [x] Organize the code with packages

## Future Adds
- [ ] Make modeling Database with MER/DER and Normalization to use a Database like SQLite or MySQL.
- [ ] ORM like Gorm to interact with a Relational-Database.
- [ ] Support Authentication with user and Bearer JSON for securing the APIs.
- [ ] Make Unit Tests.
- [ ] Make docs with GoDoc.
- [ ] Building a automatic deployment process with Makefile and GitHub Pages Deploy Action 🚀 .


