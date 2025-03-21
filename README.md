# Local Weather Backend API

An Express.js API that calls the relevant external APIs needed to run a front-end local weather app.

* [Local Weather App (React.js version)](https://github.com/autumnchris/local-weather-app-reactjs)
* [Local Weather App (vanilla JS version)](https://github.com/autumnchris/local-weather-app-vanilla-js)

---

## Built With
* [Express.js](https://expressjs.com)
* [Node.js](https://nodejs.org/en)
* JavaScript
* [EJS](https://ejs.co)
* HTML5
* CSS3
* Vanilla JS
* [OpenWeatherMap API](https://openweathermap.org)
* [GeoDB Cities API](https://rapidapi.com/wirefreethought/api/geodb-cities)
* [Axios](https://axios-http.com)
* [dotenv](https://github.com/motdotla/dotenv)
* [Normalize.css](https://necolas.github.io/normalize.css)
* [Google Fonts](https://fonts.google.com)
* [Font Awesome](https://fontawesome.com)
* [nodemon](https://nodemon.io)

## Demo

View project demo at [https://autumnchris-local-weather-backend-api.onrender.com/api](https://autumnchris-local-weather-backend-api.onrender.com/api).

## Instructions

After cloning and navigating to the repository in your command line, install the NPM packages.
```
npm install
```

Create a `.env` file in the root of the repository and add the following variables:
```
OPEN_WEATHER_API_KEY=<your-open-weather-map-api-key>
GEO_DB_API_KEY=<your-geodb-cities-api-key>
```

Run the following script in your command line if starting the repository in development mode.
```
npm run dev
```

Run the following script in your command line if starting the repository in production mode:
```
npm start
```

Go to `http://localhost:3000` in your browser.