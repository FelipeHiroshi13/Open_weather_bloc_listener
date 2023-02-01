# Open Weather Bloc Listener

A Flutter project with Bloc and a Weather API from "Open Weather Map". 

## Features using Bloc

There are many features in this project using Bloc such as:

- Change temperature between ℃ and ℉;
- Theme app changes the temperature accordingly, if it is bigger than a constant (kWarnOrNot) the theme app will be light. On the other hand, it’ll be dark;
- Bloc deals with the API response, with Weather status like initial, loading, loaded and error.

## Screenshots

|                                                                                       |                                                                                                                    |                                                                                                    |
|:-------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------:|
|           <img width="1604" alt="Initial" src="screenshots/initial.png">  Initial State            |                       <img width="1604" alt="temp_settings" src="screenshots/temp_settings.png"> Temp Settings                        |                    <img width="1604" alt="select_a_city" src="screenshots/select_a_city.png"> Select a city                    |
|           <img width="1604" alt="london" src="screenshots/london.png">  Dark Theme             |                       <img width="1604" alt="campo_grande" src="screenshots/campo_grande.png"> Light Theme                      