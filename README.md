# React Progressive Weather Web App

> A Weather Application created using React.js and the Open Weather API.

![Search](/public/images/Desktop.png)

The deployed app can be found [here](https://heuristic-blackwell-1dc524.netlify.app)

## Table of Contents:

- [General Info](#general-information)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Handling of API Keys](#handling-of-api-keys)
- [Screenshots](#screenshots)
- [Credits](#credits)
- [Contact](#contact)

## General Information

Fundamentally, this is a Progressive Web App (PWA) built using React.js. It is a weather application which can be installed on any device, by anyone.

## Installation

To install this application on your mobile device, please carry out the following instructions:

1. Navigate to the following [website.](https://heuristic-blackwell-1dc524.netlify.app)
2. Thereafter, click on the 3 dots which are positioned in the top right hand corner of your screen.
3. Scroll down to the "Install App" option and click on it.
4. Lastly, you will be prompted to 'install' the app. Once this has been selected, the weather application will then be installed on your mobile device.

## Usage Instructions

Simply enter a town or city into the input field and hit "Enter". The weather forecast for that respective area will then be displayed.

The user interface is extremely simple, intuitive and easy to use.

## Handling of API Keys

An API key was utilised & it was secured in the following manner:

- I created a '.env' file within the root folder.
- Thereafter, I added the key to this file. E.g. REACT_APP_API_KEY=enterYourKey.
  This key is now accessible by using the process.env variable. E.g. console.log(process.env.REACT_APP_API_KEY) will print the Open Weather API key to the console.
- Lastly, I added the .env file to my .gitignore file. This ensures that the .env file, which contains the key, is NOT pushed to GitHub!

## Screenshots

- **Mobile View**
  <br />
  ![Favourites](/public/images/Mobile.jpeg)

## Credits

- Build and Deploy a React PWA [tutorial](https://www.youtube.com/watch?v=IaJqMcOMuDM&list=LL&index=1) - by JavaScript Mastery.

## Contact

👤 **Riaz Karolia**

Feel free to contact me on [LinkedIn](https://www.linkedin.com/in/riaz-karolia/)
