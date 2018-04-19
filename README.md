# Weather App

Web app that allows the user to get a five-day forecast of a Canadian city via a search bar.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and/or testing purposes.

### Prerequisites
You will need to install Node.js. See below for the download link.

### Installing
1. Run ```$ git clone https://github.com/aemc/weather-app.git``` on the cli, or download the source code to a local directory of your choice.
2. Run ```$ npm install``` within the root folder to install all the necessary libraries.
3. Sign up for an api key at [OpenWeatherMap](https://openweathermap.org/).
4. Create a ```secret.js``` file and place it inside the src folder. Edit the secret file with ```export default <insert api key here>```.

### Running
1. Run ```$ npm start``` on the cli within the root of the project folder.
2. Open your browser and navigate to ```localhost:8080``` to see the app running.

### Built With
* [React](https://reactjs.org/) - A JavaScript library for building user interfaces
* [Bootstrap 4](https://getbootstrap.com/) - Frontend library
