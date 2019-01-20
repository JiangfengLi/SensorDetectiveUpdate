# Sensor Detective

Sensor detective was developed for a challenge in HackAZ 2019.
It tries to add visual mining tools to the traditional dashboard which usually
consists of simple timeseries visualization or fancy (and sometimes messy) 3d graphs
or infographics.

To see a discussion about the value of parallel coordinates in visual discovery of patterns,
see [this awesome paper](http://web.cs.ucdavis.edu/~ma/ECS289H/papers/Inselberg1997.pdf). 

## Getting Started

Just load the page and the system will start connecting sensor data from 192.168.0.3/sensorname.
For HackAZ2019 the addresses are:

- http://192.168.0.3/ircam.json reports thermal array sensor data
- http://192.168.0.3/gps.json reports gps sensor data
- http://192.168.0.3/localsensors.json reports CO2, volatile gas, ambient temperature and light

In any case changing these addresses or even mocking the sensor data should be very easy.

### Prerequisites

- Connection to the WIFI broadcasting sensor data
- Disabling CORS (Cross Origin Resource Sharing). On Chrome, there is a
[convenient addon]([https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en)
that can be used to disable CORS policy.


### Installing

There is no need for installation as this is simply a JavaScript SPA (singla page application).



## Built With

* [D3](http://www.d3js.org) - The main visualization library
* [ParCoord](https://github.com/BigFatDog/parcoords-es) - A plugin for D3 for creating the parallel coordinate plot
* [Bootstrap](https://getbootstrap.com/) - For styling
r the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Roozbeh Khodadadeh** - *Initial work* - [Github](https://github.com/roozgit)
s) who participated in this project.

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc

