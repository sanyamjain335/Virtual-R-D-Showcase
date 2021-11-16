# Virtual R&D Showcase using AFrame
The idea is to develop a WebVR application to showcase the recent Research and Development in IIIT Hyderabad.

No environment dependency for given code.

##### Watch full demonstration of the project here - `https://www.youtube.com/watch?v=wqZrPLXE2sY`

## To start the project use the following steps:-

1. Fill up research_centers.json file with research centers along with url of the images associated with perticular center in the specified format:-

    {
        "CENTER-1" : ["IMAGE-URL-1", "IMAGE-URL-2".......],
        "CENTER-2" : ["IMAGE-URL-1", "IMAGE-URL-2".......],
        .
        .
        .
        .
        .
        "CENTER-N" : ["IMAGE-URL-1", "IMAGE-URL-2".......]
    }

2. Deploy this file to a glitch project and paste project-file URL into the files entry.js(line no. 11) and fetch_json.js(line no. 1)

3. Start the project by opening entry.html file in the browser. Now Enjoy the virtual tour of R&D Showcase.

## Some glimses of Virtual R&D Showcase:-
## Entry Room
![alt text](https://github.com/sanyamjain335/Virtual-R-D-Showcase/blob/main/entry.png?raw=true)

## Room Front View
![alt text](https://github.com/sanyamjain335/Virtual-R-D-Showcase/blob/main/room-front-view.png?raw=true)

## Room Side View
![alt text](https://github.com/sanyamjain335/Virtual-R-D-Showcase/blob/main/room-poster-view.png?raw=true)

## Door(Click on it to again go to Entry Room)
![alt text](https://github.com/sanyamjain335/Virtual-R-D-Showcase/blob/main/door.png?raw=true)
