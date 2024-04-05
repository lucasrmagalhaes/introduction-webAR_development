### Introduction to Web AR development

#### Development Environment Setup
* [Web Server for Chrome](https://chromewebstore.google.com/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)
* [ngrok](https://ngrok.com/)

**Create an URL accessible by any devices with internet connection**
```
// 8887 - default port

./ngrok http 8887
```

* [Remote JavaScript Debuggin](https://remotejs.com/)

#### Course Materials
- All the examples used in the course.
    - libs
        - contains all the the libraries needed
    - assets
        - contains all the assets, including 3D models, images, videos, etc...
    - lectures
        - contains all the completed source code at the end of each lecture
    - lectures-start
        - contains the source code at the beginning of each lecture

#### 3D Rendering Basic
- WebGL
    - is a javascript api for rendering 3D graphics on browsers
    - is a cross-platform web standard so basically all major browsers support it
    - webgl code is very difficult to read and write
        - so people build more user-friendly libraries on top
            - three.js is one of these libraries

* [three.js](https://threejs.org/)
* [Installation](https://threejs.org/docs/index.html#manual/en/introduction/Installation)

```js
import * as THREE from 'three';
```

#### Tracking and AR
- Types of AR
    - barcode-like images
        - are images that has a predefined patterns
    - natural images
        - area images that can be anything typical image tracking ar applications include ar product packaging maganizes
    - face tracking
        - in face tracking augumented objects are attached to human face (facebook, instagram)
    - world tracking ar
        - people sometimes refer to it as markerless ar
        - the augmented content can be placed anywhere not restricted to particular image, face or physical objects
    - location based AR?
        - what people usually mean by that is that ar content is attached to certain geographical location like latitude and longitude