# Weather App Rebuild - IN DEVELOPMENT

This is just a note for while I'm in development stages: 

>Although there are many weather apps out in the tech world, my reason for revisiting this project wasn't to add to my portfolio. My objective is to be able to bring my new skills and enhance an old project that I didn't do very well on before. My first attempt was with Javascript, and then again in React.js afterwards. This time I'm challenging myself by trying once again, this time with Typescript. I've started the basic set up and I've already been able to do something I wasn't able to do in the past, get local storage to work for the favorites list when it's routed on a different page. I was able to do it all on a single page prior, but now that I have the favorites page working in my React.js file, I decided I wanted to convert the whole project into Typescript, better utilize bootstrap for more modern styles, and I plan to add a few more unmentioned features in the future. If you're interested in seeing where I end up with this app, feel free to give it a star or contact me to keep in touch! Thanks for reading this far!

This is a revamp of my Weather App built with React,js, TypeScript, and Bootstrap. I first built this in Javascript, then again in React.js, and now once more but enhanced with TypeScript and further modifications. The application allows users to search for weather information about different locations and provides them with the current temperature, high and low temperatures for the day, as well as a 5-day forecast. The project utilizes the OpenWeather API (https://openweathermap.org/api) to fetch weather data and displays images related to the weather conditions. As well as a favorites page to manage favorite locations.

**Check out the deployed application [In Development...](https://urlgoeshere.azurewebsites.net/).**

## Features

- Search functionality to find weather information for different locations
- Display of current temperature, high and low temperatures, and weather conditions
- 5-day forecast for the searched location
- Favorites page to store and manage favorite locations
- Clicking on favorited locations in the list will open a card with their current temp
- Responsive design that adapts to different screen sizes and devices

## Technologies Used

- React.js
- React-Router
- TypeScript
- Bootstrap
- CSS
- HTML
- RESTful API: OpenWeather API (https://openweathermap.org/api)

## Setup

To run this project, follow these steps:

1. Clone the repository to your local machine
2. Install dependencies by running `npm install` in the project directory
3. Obtain an API key from OpenWeather by signing up on their website (https://openweathermap.org/guide)
4. Create a new file named `.env` in the root directory of the project
5. In the `.env` file, add the following line and replace `YOUR_OPENWEATHER_API_KEY` with your actual OpenWeather API key: REACT_APP_OPENWEATHER_API_KEY=YOUR_OPENWEATHER_API_KEY
6. Start the development server by running `npm start`
7. Open `http://localhost:3000` in your web browser to view the site

> **Note:** Make sure to keep your API key confidential and do not commit the `.env` file to any public repositories. The `.env` file is already added to the `.gitignore`, so it won't be uploaded to the repository.

## Contact

If you have any questions or feedback about this project, feel free to contact me at [brandonctle.dev@gmail.com](mailto:brandonctle.dev@gmail.com).

Connect with me on [LinkedIn](https://www.linkedin.com/in/brandonctle/) to stay updated on my latest projects and professional profile.

You can also [visit my portfolio website](https://www.brandonle.azurewebsites.net).

Thanks for visiting!
