# owm_node-red
Open Weather Map Dashboard using Node-RED 
This is a Weather Forecast Dashboard using Open [API from Open Weather Map](https://openweathermap.org/api) 
The data is being passed through a public [MQTT broker](test.mosquitto.org) for the sake of exercise working with mosquitto (could be removed) 
Design was inspired by https://gist.github.com/djiwondee/b5b7d5da14d24e71de447e6aa290937e

## Dependencies 

### Open Weather API 
To access the free API of Open Weather Map you need to [create an account](https://openweathermap.org/) and aquire an API Key 
**Note:** It could take a couple of hours until you get an email from OpenWeather with the API key.

### Node-RED Modules
In Node-RED install the modules: [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard) and [node-red-node-openweathermap](https://flows.nodered.org/node/node-red-node-openweathermap) This imports all the used widgets and icons. Overview of the [weather icons](https://github.com/Paul-Reed/weather-icons) 

## Flow 
![Node-RED visualization of the flow](https://github.com/georgievaz/owm_node-red/blob/main/flow.PNG)

## Dashboard
![Screenshot of the Weather Forecast Dashboard](https://github.com/georgievaz/owm_node-red/blob/main/dashboard.PNG)
