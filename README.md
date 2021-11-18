# Introduction

The Digital Twin Development Tool enables the users to develop digital models/twins of physical entities. The digital twins have the ability to replicate the physical behavior in digital environment through the injection of relevant data feeds. The digital twins can be stored and shared as part of learning and experimentation purposes.

The Digital Twin Development Tool enables the users to develop digital models (twins of physical entities). The kit does not require you to have a physical model, but in terms of the use case in iPRODUCE you will probably have one.

These models will allow OpIS users to develop, design, and deliver learning and training material using advanced digital technologies. 

Using a digital twin, activities can be simulated on a small scale and learn before they are used on a large scale without wasting any resources or damaging any equipment.

A Digital Twin can execute synthetic scenarios as part of training and support learning activities.  

# Overview
This section provides a slightly more detailed view of the documentation. This is so that you can preview the essence of the document without having to unzip and extract the word document.

## Current Version

The current version is at the prototype stage.

ICE are presently working on the fuller version which should be easier to integrate new models with.

## The Zip File
The ZIP file should be extracted and the word document read in full before commencing activities with this project.
## Three.JS
Three.js is a JavaScript library for displaying 3D models on webpages. We used the library to create models of our physical factory. You will need to be able to develop in JavaScript to follow this section of the guide.

The word document contains more information on how we use ThreeJS.

Resources
* [ThreeJS](https://threejs.org/)
* [Documentation](https://threejs.org/docs/index.html#manual/en/introduction/Creating-a-scene)
* [Examples and videos](https://threejsfundamentals.org/threejs/lessons/threejs-responsive.html)
* [Book Guide Written by one of the Developers](https://discoverthreejs.com/)
* [Book written by Jos Dirksen](https://www.packtpub.com/product/learn-three-js-third-edition/9781788833288)

## Physical Model
The physical model used as in the kit is base on the Fisher Technik hardware components. The website is [fischertechnik.de](https://www.fischertechnik.de/en).

## Technical Stack
* Grafana - Analytics Dashboard
* MySQL - Data set for driving and animating the model/hardware
* JavaScript - Animating the model


# Creating a New Model/Twin

To create a Digital Twin a 3D model is created. This can be made using ThreeJS or another system.

Then bespoke code is written in JavaScript to animate the model.

Should you wish to animate the model a data set must be imported into the SQL Database.

Once the model and data set have been imported, you will also need to create a BPMN flow diagram to orchestrate the model with the data. The BPMN will integrate the 3D model, data set and the code to animate the model such that a fully working model is realised.

