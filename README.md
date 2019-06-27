# City Flood Analyzer

Background:
   It is not rare to see city flood around the world. Its impact is huge, sometimes it can be a disaster. 

Idea:
   Sending real-time images & videos taken by city-wide surveillance cameras & smart phone     
   to Flood Analyzer (neural network model we build) which classify water depth
   on city roads based on reference objects such as car and pedestrian, 
   then send water depth information to website or smart phone APP. 

The project could keep government and citizens acknowledged of the real-time city flood severity so as to choose the safest road where with lowest water depth.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

```
x86_64 linux OS, such as Ubuntu16.04 or MacOS10.xx 
```

make sure below package installed. You can install with pip3

```
python3
tensorflow
pytest
requests
opencv-python
numpy
Cython
codecov
```

### Installing by the setup.sh


```
cd flood_analyzer/
```

```
chmod +x setup.sh
```

```
./setup.sh
```
## Running the tests

Start the WebUI

```
cd flood_analyzer/webUI
```

```
npm start 
```

Upload a phote with car in city flood, then you will it is classified into one of four categories of water depth.


## Built With

* Node.js - The web framework used
* darkflow - https://github.com/thtrieu/darkflow

## License

This project is licensed under the Apache 2 License - see the [LICENSE.md](LICENSE.md) file for details
