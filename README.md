## The nearest object localization through 3D sthereoscopic camera reconstruction using an embedded system

This work was the bacherlor thesis of Jonathan Vargas and Diego Navas at Escuela Politécnica Nacional.

## Abstract

This work presents the design and implementation of a portable system that allows detecting the nearest object’s location through 3D reconstruction using a stereoscopic camera. The system transforms the environment information in front of the camera to a tridimensional point cloud that is filtered digitally in order to determine the nearest object spatial localization. The whole processing is performed in an embedded system which is powered by a lithium-polymer power bank. All devices are placed in a vest to be worn by the user. The vest gives improvements in weight, portability as well as autonomy and comfort. Remote graphical interface visualization is used as a way to verify the correct work of the system and also it is capable to observe the reconstructed environment, the nearest object and its localization respect to the user.

You can download this work [here](http://bibdigital.epn.edu.ec/bitstream/15000/19155/1/CD-8536.pdf).


## Components
This figure represents the main components of the prototype. It was composed of a local program and a remote HMI for analitycs purpose. 

<p align="center">
  <img height="320" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398527/wordpress_Jonathan/thesis1.png">
</p>


## Algorithm
An algorith for filtering point cloud data, using PCL library, was implemented in order to find the nearest 3D point.

<p align="center">
  <img height="320" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398526/wordpress_Jonathan/thesis2.png">
</p>


## 3D Scan
This figure shows a point cloud reconstruction.

<p align="center">
  <img height="200" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398525/wordpress_Jonathan/thesis3.png">
</p>


## PIMI-1512 Project
A 3D reconstruction was the first step in order to create a ETA (Electronic Travel aid system for blind people). In the PIMI-1512 project at Escuela Politécnica Nacional the previous work was combined with machine learning, 3D sound, and a IMU sensor for detecting head rotation.

<p align="center">
  <img height="320" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398529/wordpress_Jonathan/research3.jpg">
</p>

## Blind people testing
There were some testing using obstacles and blind people in order to probe user experience. The system can detect and recognized obstacles in the environment and the users had to avoid them

<p align="center">
  <img height="320" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398530/wordpress_Jonathan/research2.jpg">
</p>

<p align="center">
  <img height="320" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398531/wordpress_Jonathan/research1.jpg">
</p>

## Research team
The 3D audio, machine learning and 3D reconstruction teams. 
<p align="center">
  <img height="350" width="480" src="https://res.cloudinary.com/dnv0qwkrk/image/upload/v1601398528/wordpress_Jonathan/research5.jpg">
</p>



## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Authors 2019 © <a href="https://www.jonathanvargas.ml" target="_blank">Jonathan Vargas</a> and Diego Navas.

