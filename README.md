# Book Search Engine: MERN Stack

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents :books::card_index_dividers:

1.  [Description](#Description)
2.  [Installation](#Installation)
3.  [Project Usage](#Project-Usage)
4.  [License Information](#License-Information)
5.  [Testing Instructions](#Testing-Instructions)
6.  [Heroku Application Link](#Heroku-Application-Link)
7.  [Contributors](#Project-Contributors)
8.  [Contact Info](#Questions)
9.  [Screenshots](#Screenshots)

<br>

## Description

This application entails a fully functioning Google Books API search engine built with a RESTful API, which has been refactored to be a GraphQL API built with the Apollo Server. The app was built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API.

<br>

## Installation :hammer_and_wrench::gear:

_Application Dependencies Include_

- Mongoose
- Express
- React (-dom/router-dom/-scripts)
- Node.js
- Apollo-Server
- Apollo-Server-Express
- GraphQL
- Bootstrap
- JWT
- Heroku

_Files Created to Make PWA Budget Tracker Functional Include_

- **manifest.webmanifest** - Provides information about this PWA in a JSON text file which is necessary for the app to be downloaded and be presented to the user similarly to the native app. (i.e you can download the app to your home screen of whatever device and have the same clean presentation)

- **service-worker.js** - This file is a script which the browser runs in the background that is essentially a JavaScript file that caches all of the Budget Trackers data and retrieves resources from the cache. You can view the included files in the app's cache here (all the public folders).

- **indexdb.js** - This file allows for the Budget Tracker to have dynamic content by allowing for the user to input withdraws or deposits, offline, and have those transactions automatically uploaded when back online. This file works with the Budget Tracker DB and creates a Budget Tracker Store to hold all of the inputted user transactions. In essence, this file creates a "waiting room" for the transactions to interact with the application.

_Additional Install Instructions Include_

- Run NPM Install to utilize package.json dependencies
- server.js file was updated to reflect a const PORT with the process.env path, along with the proper syntax to connect to our Mongoose DB.
- index.html file = link to manifest.webmanifest was included in head of document, along with scripts for the indexdb.js and service worker (both at the base of the index.html)
- Utilizing MongoDB Atlas and Heroku, a Budget_Tracker database was created and then linked for proper deployment.

<br>

## Project Usage

_User Story_<br>

AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase

<br>

## License Information

The MIT License is a permissive free software license originating at the Massachusetts Institute of Technology in the late 1980s. As a permissive license, it puts only very limited restriction on reuse and has, therefore, high license compatibility.

<br>

## Testing Instructions

1. Follow the Heroku app link located below.
2. At the top right of the screen, create a new account by signing up with name/email/password. Or if returning, login with current credentials.
3. Utilize the search box to enter in any book of your choosing (or author, title, description) and click "Submit Search".
4. You will see a list of the matching books below the search bar relevant to your search. From here you have the capability to save as many books as you like!
5. After your books are saved, you can click on "See Your Books" to view your selections. From here, you have the capability to delete any book which you have already saved previously.
6. The application runs off of Heroku, while connected to a MongoDB database, so all of your saved books will be saved on local storage in addition to back end server-side storage.
7. Please feel free to clone the repo to test on your local machine. You will need to NPM I for the dependencies (including GraphQL), and make sure you are connected to a MONGODB to run with full intended functionality.

<br>

## Heroku Application Link

### **https://polar-meadow-78874.herokuapp.com/**

<br>

## Project Contributor :man_technologist:

Adam Spiegel<br>
Full Stack Web Developer

<br>

## Questions?

### Please find my contact information below to reach out and collaborate!

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:AdamSpiegel23@gmail.com) [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AdamSpiegel) [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adam-spiegel-3086687/)

<br>

## Screenshots - Application Functionality

<br>

## _Successful Build_

![Screenshot1](./images/Screenshot1.png)

<br>

## _Coding Student Book Search Results_

![Screenshot2](images\Screenshot2.png)

<br>

## _Parent Book Search Results_

![Screenshot3](images\Screenshot3.png)

<br>

## _View Your Saved Book Collection_

![Screenshot4](images\Screenshot4.png)

<br>

## _While Browsing, View The Books You Already Saved_

![Screenshot5](\images\Screenshot5.png)

<br>

## _Local Storage Array of Your Saved Books_

![Screenshot6](\images\Screenshot6.png)

<br>

## _MongoDB - Backend Book Search Saving Capabilities_

![Screenshot7](\images\Screenshot7.png)

<br>

![Screenshot8](\images\Screenshot8.png)
