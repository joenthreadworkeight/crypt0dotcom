# crypt0dotcom


## Task 1  
### Setup guide  
#### Run via Postman  
1. Download Postman  
> https://www.postman.com/downloads/  

2. Install and Open Postman  
3. Import JoeNg-Test1.postman_collection.json into the postman  
File -> Import...

4. Click "Send..." button
5. You will get the result at the bottom of Postman


#### Run via newman (console)
1. Download Nodejs
> https://nodejs.org/en/

2. Install Nodejs
4. Download or checkout the JSON file (JoeNg-Test1.postman_collection.json)
3. Open command line and run the following command
> npm install -g newman
4. In the console, change the location to the json file location.
> cd <path-to-json-file-folder>
5. Run the following command
> newman run JoeNg-Test1.postman_collection.json
6. You will get the result via the console
