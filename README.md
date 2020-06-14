![Logo](https://github.com/TxyShannon/Relevance-WARDEN_SCDFXIBM/blob/master/docs/Logo.png)
# Team Relevance - Project Warden
This is a project done for SCDFxIBM Lifesaver's Innovation Challenge 2020. 

## Members
- Shannon Tan [![LinkedIn badge 1](https://img.shields.io/badge/LinkedIn-Connect-Blue.svg)](linkedin.com/in/txy-shannon)

I have been through several Game Jam, App Development competitions but this is my very first taste of a Hackathon.
Aiming to provide a beneficial solution to society, I hope to one day pitch the next-big idea!

- Tan Tian Shou [![LinkedIn badge 3](https://img.shields.io/badge/LinkedIn-Connect-Blue.svg)](https://www.linkedin.com/in/tantianshou/)

Digipen Final year student pursuing BA in Game Design. Enjoys competition but even more so the camaraderie and memories that are build within it.

- Chong Wei Xiang [![LinkedIn badge 3](https://img.shields.io/badge/LinkedIn-Connect-Blue.svg)](https://www.linkedin.com/in/weixiangcwx)

A final year student in SIT Digipen pursuing BSc in Real-Time Interactive Simulation. First attempt in a Hackathon is always bitter, but 
I'm always eager to continue pushing myself harder and strive for the better.

- Goh Kai Jie, Keith [![LinkedIn badge 4](https://img.shields.io/badge/LinkedIn-Connect-Blue.svg)](linkedin.com/in/goh-kai-jie-keith)

Always down to learn more

## Contents  
1. [Short Description](#Short-Description)
2. [Pitch Video](#Pitch-Video)
3. [Architecture](#Architecture)
4. [Long Description](#Long-Description)
5. [Project Roadmap](#Project-Roadmap)
6. [Getting Started](#Getting-Started)
7. [Running the Tests](#Running-the-Tests)
8. [Live Demo](#Live-Demo)
9. [Built with](#Built-with)
10. [Acknowledgement](#Acknowledgement)

## Short Description
### What's the problem?
Infrastructure is getting “smart”, with sensors and Internet of things (IoT) increasingly embedded in the built environment. We need to leverage the existence of these devices to help quicken the response time for disasters (such as developing fires) whilst cutting down the need of manpower. 

### How can technology help?
With Iot enabled sensors, inter-weaving systems can be set in place to continuously monitor a wide area to perform intervention of potential disasters with the aid of the public. These intervention will reduce the need for emergency resources.

### The idea
Using temperature sensors and IP Cameras, a smart environment can monitor its vicinity and request assistance from the public. When a temperature sensor is triggered, the inter-weaving system can use a nearby IP Camera to perform Object Detection as verification of a potential disaster. If the situation is un-examinable or if it is minor, the system can prompt nearby public members to provide human evaluation of the affected area. Else, the system would immediately notify authorities. This enables a quick initial response. 

## Pitch Video
[![Click Here]](https://youtu.be/UH568Olv_Ws)

## Architecture
![architecture png](https://github.com/TxyShannon/Relevance-WARDEN_SCDFXIBM/blob/master/docs/Info1.jpg "Architecture")

## Long Description
Details can be found [here](https://github.com/TxyShannon/Relevance-WARDEN_SCDFXIBM/blob/master/docs/description.md).

## Project Roadmap
![roadmap png](https://github.com/TxyShannon/Relevance-WARDEN_SCDFXIBM/blob/master/docs/Info3.jpg "Roadmap")

## Getting Started

### Tensorflow demo
Due to the time constraint, only local deployment of the object detection demo is available, in attempt to simulate imaging analysis from an ip camera to identify a fire hazard.

### Prerequisite
- Webcam
- A fire (Or a picture of it)
- You not wearing anything orange

**Note:** You will require Node 8.10.0 or later in your local deployment machine.

### To begin
- Navigate to source > TensorFlow > object-detection-webcam-style in your preferred cli
- Run the App with **npm start**
- Launch [http://localhost:3000](http://localhost:3000) in your browser.
- A pop-up should appear to indicate permission for webcam access. Click **"Allow"** to gain access to the webcam.

By intended behavior eventually, the webcam should be pinging node-red with a boolean of "true" when a fire is detected, and "false" when it is not.

## Work in Progress
[![Demo_1](https://img.shields.io/badge/NodeRed-Down-Red.svg)](https://project-warden.mybluemix.net/red/#flow/9168237a.a1f8b)

## Built with
- [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - Database
- [IBM Node Red](https://cloud.ibm.com/catalog?search=node%20red#search_results) - Communication between IoT enabled devices

## Acknowledgement
 - object-detection-live-stream project, buordakos1, for providing the initial framework <br/>
 - node-red tutorials for helping alot

