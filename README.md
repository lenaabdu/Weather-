Weather App :-
This project is a Weather forecast app that shows the weather forecast of your Current location and the supplied city. 
It shows a time, date, city,country ,image indicating the weather conditions ,and a basic description of the weather for the current location using the OpenWeather API to retrieve forecast information.
also It display temperature, humidity, wind Speed Visibility,image  and a basic description for the city supplied by user.
in the field provided, type the city of which you want to know the current weather condition. 
on the main screen provided, you will find the current weather status in your location, automatically.

A-Follow Below Instructions to download the code file:
   1- On GitHub, navigate to the main page of the repository.
   2- Above the list of files, click Code.
   3- To clone the repository using HTTPS, under "Clone with HTTPS", click ![image](https://user-images.githubusercontent.com/54982546/133905176-8b1ee8f6-e7f4-4d3a-9845-6a3a9f84a0ce.png)
   To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click ![image](https://user-images.githubusercontent.com/54982546/133905194-a9ab76cf-315e-408a-bbd0-9b981e9f2690.png)
   To clone a repository using GitHub CLI, click Use GitHub CLI, then click ![image](https://user-images.githubusercontent.com/54982546/133905198-c87b0df4-9b32-4f8b-9d70-809608323790.png)
   4- Open Git Bash.
   5- Change the current working directory to the location where you want the cloned directory.
   6- Type git clone --branch <branch name> <URL>, and then paste the URL you copied earlier.($ git clone --branch mater  https://github.com/lenaabdu/Weather-.git).
   
   
B- Install packages:
   1- npm install.
   2- react-live-clock(npm install --save react react-live-clock / yarn add react-live-clock).
   3- react-animated-weather(npm install react-animated-weather / yarn add react-animated-weather).
   4-axios (npm install axios /yarn add axios )
   
   
C- Get your API Keys
   To get weather data we need to use API to fetch data & for that i have used Open Weather Map API. Its free to use & highly accurate.
   To get your API key:
     1- sign up into Open Weather.
     2- confirm your email account.
     3- you will get Your API key( Your API Key will be sent to to mail and also you can find your key into dashboard in the Open Weather API website).
     4- when you got your API key put the key in ( apikeys.js){
           module.exports = {
                key: {API KEY here }
                base: "https://api.openweathermap.org/data/2.5/",
               };     } 
   
D- Run your code :
     yarn start /  npm start 
    Runs the app in the development mode.
    Open http://localhost:3000 to view it in the browser.
