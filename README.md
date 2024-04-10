# SMART 2024 Template Repository

![Insalogo](./images/logo-insa_0.png)

Project [SMART(PLD)](riccardotommasini.com/teaching/smart) is provided by [INSA Lyon](https://www.insa-lyon.fr/).

Students: Irvin Cote, Arthur Galet, Josue Venegas, Alexandre Rosard, Abdel Latif Hamdan

### Abstract
Low cost, open source GPS tracking system.

## Description
We think that commercial GPS solutions come at an excessively high price, either
as a one time purchase (~300€) or with a montly subscription (~7€).  
And so we wonder if we can come up with a less expensive alternative...

## Project Goal
The project goal is to develop an opensource GPS-LTE tracking system composed of the following 
3 components : 

-The firmware (either written in RUST or C++)  
-The web server that handles the communication with the tracker  
-A web client to view and control the tracker  

------------ Additional precisions ------------------  
|                                                   |  
|     One of the applications we can think of       |  
|     is tracking the location of a stolen object   |  
|                                                   |  
|                                                   |  
-----------------------------------------------------  

## Libraries and languages

- Angular (js) (front end app)  
- Rocket (rust) (Web server)  
- nrf connect sdk (c) (firmware)  



## Requirements
The project would be based on Nordic Semiconductor's nRF9160 SIP and the software POC
would be developped off of the associated developpement board.
