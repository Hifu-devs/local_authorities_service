# Local Authorities Service

## What help is nearby?

### Overview

local Authorities is a microservice used by the [hifu-api](https://github.com/Hifu-devs/hifu-api) application.  It has one endpoint `/sheriff`. The microservice finds the nearest sheriff's office to the provided lat/long parameters.

### Authors

- [Margo Flewelling](https://github.com/margoflewelling)
- [Krista Stadler](https://github.com/kristastadler)
- [Brian Greeson](https://github.com/brian-greeson)

### Local Setup

- Clone
- bundle
- rackup


### Production

The production version of this microservice is deployed to [https://hifu-authorities-service.herokuapp.com/](https://hifu-authorities-service.herokuapp.com/)


### Endpoints

- get `/sheriff` 
   - parameters:
     - `lat`
     - `long`