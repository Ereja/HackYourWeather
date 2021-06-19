# HackYourWeather
Simple backend application that displays current weather of chosen city.

# Created using:
## Used API:
[OpenWeatherMap](https://openweathermap.org/) API used to get all the weather data

##NPM packages used: 
[Axios](https://www.npmjs.com/package/axios) used for fetching data from OpenWeatherMap
[Express](https://www.npmjs.com/package/express) for creating a server
[Express Handlebars](https://www.npmjs.com/package/express-handlebars) for rending HTML files from backend

##Others:
[CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) for styling and making sure that application is fully responsive, without using media querries


### Demo
Online Deployment of this project is available at [HackYourWeather](https://hackyourweather.herokuapp.com/).


### If you want to run this application on your machine:

To get started you can simply clone the repo, in the root folder create **sources** folder and inside it, create a keys.json file, with API key you can get from [OpenWeatherMap](https://openweathermap.org/) ("API_KEY" = "Your key") and then install the dependencies in the root folder
    
| Steps   |with [NPM](https://www.npmjs.com/) |
| ------- | --------------------------------- | 
| Install |npm install                        |
| Run     |node server.js                     |

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
