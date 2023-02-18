# Auth0 React Kranio Demo

![oauth-implicit-grant-flow](https://user-images.githubusercontent.com/56135515/219876025-754f519d-797b-497c-aa75-560310e5e519.png)

## Add credentials file

src/auth_config.json

```
{
  "domain": "default-example.us.auth0.com",
  "clientId": "EXAMPLECDMqEXAMPLE0BWGEXAMPLE",
  "audience": "api-identifier-example"
}
```

To run the sample follow these steps:

## Set the Allowed Callback URLs in the Application Settings to

http://localhost:3000

## Set Allowed Web Origins in the Application Settings to

http://localhost:3000

## Set Allowed Logout URLs in the Application Settings to

http://localhost:3000

## Project setup

npm install && npm start

## You can also run it from a Docker image with the following commands:

### In Linux / macOS
sh exec.sh
### In Windows' Powershell
./exec.ps1
