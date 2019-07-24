# [Apis and Microservices Projects - Request Header Parser Microservice](https://github.com/steliancorbut/Timestamp-Microservice)

## Preview

**[View Live Preview](https://cooked-cabbage-1.glitch.me/)**

## Download and Installation

To begin using this app, choose one of the following options to install/get started:
* [Download the latest github repo archive](https://github.com/steliancorbut/Timestamp-Microservice)
* Clone the repo: `git clone https://github.com/steliancorbut/Timestamp-Microservice.git`

## Usage

After download/unzip/installation, in resulted folder run:
- `npm install` for node_modules. (Node.js must exist)

to run/develop run
- `node server.js` and the server will listen at http://localhost:3000
- in browser access http://localhost:3000 and give an url like in Example Usage below
and will get an output like {"unix":1451001600000, "utc":"Fri, 25 Dec 2015 00:00:00 GMT"}

#### Example Usage

- input url in browser `http://localhost:3000/api/timestamp/2015-12-25` and will get an output like 
- example Output `{"unix":1451001600000, "utc":"Fri, 25 Dec 2015 00:00:00 GMT"}` 

## Copyright and License

Code released under the [MIT](https://github.com/steliancorbut/Timestamp-Microservice/blob/master/LICENSE) license.
