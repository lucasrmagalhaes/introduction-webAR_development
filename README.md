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
