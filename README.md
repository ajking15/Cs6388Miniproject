# Petrinet Miniproject - VideoOnDemand 

## Installation
First, install the myminiproject following:
- [NodeJS](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- Run 'docker-compose up -d'
- Go to Localhost:8888

## Modeling
This application models a Video On Demand Content delivery appliation. Modeling from logging in to the application and all they way viewing uploading video. 
This modeling with help understand how a video is processed till uploading. This can be used to design and implemnt a content delivry system. 

A token can traverse throuout the model from end to end. 
- Each Node is set as Place or Transition
- Each edge is set as Place-Transtion And Transition-Place 

SVGs are used to indicate how many tokens are assigned to a Place node.

## Classification
The application has a plugin enabled that identifies whether your model can be classified as one of the following
1. Classifier


## Visualization
The application provides a PetriNet view and simulates the flow of the Video Content Delivery Application in a graph layout. At the moment
this visualization is limited to a single token moving with a triggered annimation  but an support more.
