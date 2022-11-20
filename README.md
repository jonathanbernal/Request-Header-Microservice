# Request Header Parser Microservice

With this microservice, you can inquire about some of your system information on your browser. An API call to the website through https://localhost:3001/whoami will provide you with information about your Web browser and OS.

## How to Install
1. Make sure Node.js and npm are installed on your computer. Typing in `node -v` and `npm -v`, respectively on your command line will let you know if they're installed.

2. Run `npm install` on the command line. You can use VSCode's built-in cmd to do this. This will install all the packages that are required to run the project.

3. Start the server with `npm start`.

## How to Run
1. Type in `npm start` to start the server. 

2. Make an API call to the server by going to https://localhost:3001/whoami. This will provide you with a JSON object that
contains the information about your computer, such as IP address, language, and OS information.

## Other Things You Can Do
You can extend this project by adding more HTTP headers to the API call method in index.js. Look up [HTTP Request Headers](https://developer.mozilla.org/en-US/docs/Glossary/Request_header) for more info.
