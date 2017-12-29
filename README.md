# Introduction 
Demonstration of securing APIs in Golang with JWT frameworks

Frameworks utilised
- https://github.com/dgrijalva/jwt-go
- https://github.com/auth0/go-jwt-middleware

## To run the Sample
```bash
go build main.go
./main
```

## Using PostMan to get Token
<img width="1258" alt="screen shot 2017-12-28 at 12 54 09" src="https://user-images.githubusercontent.com/676905/34411406-4b775e18-ebce-11e7-84bc-20511edc03a4.png">

## Getting the Product List with a signed Bearer Token
<img width="1248" alt="screen shot 2017-12-28 at 12 56 35" src="https://user-images.githubusercontent.com/676905/34411477-be71f4c8-ebce-11e7-956c-b087c9632a73.png">

##Auth0 Implementation 

Refer to auth0-implementation to get the code, secrets and ids are avaiable on request

### Start page
<img width="1404" alt="screen shot 2017-12-29 at 11 52 38" src="https://user-images.githubusercontent.com/676905/34436807-158e8cc2-ec91-11e7-9a9b-ee9859271c3b.png">

### Authentication
<img width="1309" alt="screen shot 2017-12-29 at 11 52 52" src="https://user-images.githubusercontent.com/676905/34436826-3ce357b2-ec91-11e7-9302-31720333d011.png">

###  Signed In
<img width="1456" alt="screen shot 2017-12-29 at 11 53 10" src="https://user-images.githubusercontent.com/676905/34436848-5739d9ec-ec91-11e7-99a2-c6e3f64f89a7.png">

### JWT Inspection 
Access Token
<img width="1305" alt="screen shot 2017-12-29 at 11 53 33" src="https://user-images.githubusercontent.com/676905/34436887-b52b4b8a-ec91-11e7-9288-1085616d9fa6.png">
ID Token
<img width="1190" alt="screen shot 2017-12-29 at 11 53 49" src="https://user-images.githubusercontent.com/676905/34437032-bba9c38c-ec92-11e7-97f7-c3f42b116d7f.png">

### Logging Console output for Requests 
<img width="1424" alt="screen shot 2017-12-29 at 12 03 06" src="https://user-images.githubusercontent.com/676905/34436901-d968b744-ec91-11e7-8830-305cca8aafdc.png">

### Local browser storage variables
<img width="1018" alt="screen shot 2017-12-29 at 12 02 00" src="https://user-images.githubusercontent.com/676905/34436944-3b556fe2-ec92-11e7-9328-7421d8271c69.png">
