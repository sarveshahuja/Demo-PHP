# Fuel (for Node.js)

This application allows users to utilize Salesforce Marketing Cloud's Fuel Auth, REST and SOAP libraries for Node.js

Learn more about our Fuel Platform's Auth, REST, and SOAP libraries along with documentation and examples:
* [AUTH][1]
* [REST][2]
* [SOAP][3]

For step-by-step instructions on creating a Salesforce Marketing Cloud ClientID and ClientSecret, visit:
[Salesforce Marketing Cloud - App Center] [4]


## Deploy to Heroku

You can deploy this app to Heroku and have it up and running instantly.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


## Installing the Application

To install this application locally, type the following in command line

```
git clone git@github.com:kheldman/Fuel-Node-Heroku.git
cd Fuel-Node-Heroku
npm install
```
 
Note: `npm install` will error if you're using node version 0.8 with developer dependencies. To have a successful install for testing/contributing use `npm install -g npm@1.2.8000` and the issue should be resolved.


### Running the Application

Follow these instructions to run the application on your local machine:

1. Change the current directory to Fuel-Node-Heroku
2. Execute the follwoing command: `node app.js`
3. Open the following page in your web browser: [http://localhost:3000] [5]



[1]: https://github.com/ExactTarget/Fuel-Node-Auth/wiki
[2]: https://github.com/ExactTarget/Fuel-Node-REST
[3]: https://github.com/ExactTarget/Fuel-Node-SOAP
[4]: http://code.exacttarget.com/apis-sdks/rest-api/using-app-center-to-get-an-api-key.html
[5]: http://localhost:3000
