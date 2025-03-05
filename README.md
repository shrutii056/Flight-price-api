##Flight-Price-Api
-- Data Sample in Body --
    
      {  
        "source": "patna",
        "destination": "pune",
        "flight": "Air-India",
        "price": 5000
       }
-## Routes & URL
- **https://flight-price-api-4.onrender.com/**
 -<p> Home </p>

- **https://flight-price-api-4.onrender.com/flight**
 -<p>To get all Flight hit the URL in your Postman with <b>Get Request</b></p> 

- **https://flight-price-api-4.onrender.com/flightall**
-   <p>To get flight and price according to Source & Destination hit the URL in your Postman with <b>Get Request</b></p>  <br/>

- **https://flight-price-api-4.onrender.com/flight/:id**
- <p>To UPTADE Flights data hit the URL in your Postman with <b>PATCH Request</b></p>

<br />


## Requirements

For development, you will only need Node.js and a node global package installed in your environement and mongodb for database.

### Node

- Node Installtion on Windows
  Go on to the [official Node.js website](https://nodejs.org/en/) and download the installer. Also, be sure to have `.git` available in your PATH,
  `npm` might need it (You can find [git](https://git-scm.com/)).
- Other operating System
  You can find more information about the installation on the official [Node.js website](https://nodejs.org/en/) and the official [NPM website](https://www.npmjs.com/).

If the installation was successful, you should be able to run the following command.

```
$ node --version
v16.13.0

$ npm --version
8.2.0
```

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

```
$ npm install npm -g

```

<br/>

## To run the project on your local machine:

1. Open terminal.

2. Change the current working directory to the location where you want the cloned directory.

   ```
   $ git clone https://github.com/MohdSabir111/Flight-Price-Api

   ```

3. Install all the dependencies by running :

   ```
   npm install

   ```

4. Run npm start to run the project at local host, port 8000:

   ```
   $ npm start

   ```

<br/>

