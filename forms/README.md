## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
Ans: the url in action is pinged with the user input

2. What is the purpose of the _method_ attribute in the _form_ tag?
Ans: the rest method get protocol is to be invoked and responded accordingly

3. What is the purpose of the _name_ attribute in the _input_ tag?
Ans: the name associated with the input provided so that the server side code can use this name
and extract the information from the request

4. What is the purpose of the _type_ attrbute in the _input_ tag?
Ans: type of the input the user needs to enter

5. What is the purpose of the _label_ tag?
Ans: Information displayed to user about the input required

6. What is the purpose of the _required_ attribute?
Ans: whether the field can be skipped or not i.e., optional field or not

